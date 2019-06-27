# Bayesian A/B Testing
### A quick exploration into Bayesian A/B Testing for email CTRs

Front-end web developers are interested in which design of their website yields more sales or some other metric of interest. They will route some fraction of visitors to site A, and the other fraction to site B, and record if the visit yielded a sale or not.

Forget everything you know about statistical testing for now. Let's start from scratch and answer our customer's most important question directly: what is the probability that the CTR for site A is larger than CTR for site B given the data from the experiment (i.e. a sequence of 0s and 1s in the case of click-through-rate)?
