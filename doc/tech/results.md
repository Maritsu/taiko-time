# Results screen
_From the tech side :o_

## Judgement and combo counting
As mentioned in the gameplay technical documentation, every non-miss hit will increase a hidden counter for every non-miss judgement: `Great` and `Good`.
On top of that, they will increase a combo counter. However, every miss will reset the combo counter.
Separate from the combo counter will be a maximum combo counter, which will only increase when the current combo rises above the maximum one and will be shown on the results screen..

## Accuracy
The accuracy will be represented as a fraction: the numerator will be added to with every hit, and the denominator will be a constant value, equal to the maximum value.
Then, at the end of the chart, the fraction will be converted to a percentage and shown on the screen.

## Grade
The grades, their requirements and their rewards are as follows:

| Grade | Requirement  | Reward           |
|:-----:|:------------:|:----------------:|
| S+    | All Perfect  | 3 coins          |
| S     | Full Combo   | 2 coins          |
| A     | 95% accuracy | 1 coin           |
| B     | 90% accuracy | None             |
| C     | 80% accuracy | None             |
| D     | Clear        | None             |
| F     | Fail         | Instant death :) |
