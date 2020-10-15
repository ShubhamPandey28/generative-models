## CYCLEGAN

- It is a method to sample data from 1 type of distribution using other type of distribution and simultaneously vice versa.

- Here image sampling is done same as DCGAN.

- Also as 4 heavy models are trained it was not possible to do it on a cpu and it was taking a lot of time on my GPU so I used tensorflow's distributed TPU training strategy to overcome it. It still can be optimized by using ```strategy.run``` with custom triain_steps.
