This **Python code** has been written using **Google.Colab** for calculating the Posterior Distribution of p given X<sub>1</sub>= x<sub>1</sub>, . . . , X<sub>n</sub> = x<sub>n</sub>. The problem is explained as follows.
Let X<sub>1</sub>, . . . , X<sub>n</sub> *c.i.i.d.* ∼ *Bernoulli*(p) and let p have a discrete prior distribution π<sub>k</sub> = π(p<sub>k</sub>) on a finite set of K numbers 0 < p<sub>1</sub> < . . . < p<sub>K</sub> < 1.
After the short code for calculating the posterior distribution, a brief clinical example is presented. This involves a diagnostic test for a disease that can yield either positive (1) or negative (0) results. Our goal is to estimate the probability p that a patient has the disease using a set of test results and prior probabilities.
* We have conducted a diagnostic test on 7 patients, and the result is shown in the vector **X**.
* The possible values for the probability p that a patient has the disease are shown in the vector **P**.
* Based on previous studies, the prior probabilities for each possible value of p are shown in the vector **prior**.

**Output:** The code outputs the posterior probabilities for each potential p based on the test results and prior probabilities. This helps us understand the revised beliefs about the probability p that a patient has the disease after taking the new test data into account.
