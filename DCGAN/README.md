## DCGAN

- Sampling images using normal distribution.

## explaination

- Suppose we have to sample data from unknown distribution ( let pdf be Py). So we some other distribution (let the random variable be z) so we want to get a function G such tha G(z) = P(y) then we can sample from z ( normal in this case ) which is a known distribution and G(z) is a sample from P(y) distribution.

## Approach 

- It is simple first we have generator function G which generates the sample using normal dist. and there anthor function Discriminator D which tells is it from the target distribution. As G(z) wants to converge to P(y) G tries to fool D and D tries to make its prediction better. hence both gets better by competing we get the desired G.