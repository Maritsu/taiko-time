# Rsults screen

```mermaid
flowchart TD
    RS(Results screen: good/bad/miss, accuracy, combo, grade)
    RS -->|Song failed| GP0[Death]
    RS -->|Song cleared| GP1(Give coins)
    GP1 --> 9999[Level end]
```

## Overall UI
A big rectangle in the center of the screen, with the following elements:
+ song title
+ judgement counters: good/bad/miss
+ combo and accuracy counters
+ big grade symbol
+ mini coins symbolizing actual rewarded coins
