# CS769-Project - Comparison of Multi-Arm Bandit Policies

In this project we have implemented various Multi-Arm Bandit policies such as epsilon-greedy, explore-only, exploit-only, epsilon-decay, UCB, and Thompson Sampling. The rewards of the arms of the bandits are drawn from a Gaussian distribution in our case of the implementation. Then contextual bandit algorithm (epsilon-greedy) is used in a real world dataset, Bibtex and the results are shown. 

Note1: The contextual bandit runs with the "Bibtex" dataset

Note2: The pre-processing code of the Bibtex dataset is not of our own, and we have used it as is from the library

Note3: The Bootstrapped UCB is not verified on larger distributions. 
The upper confidence bound is implemented using the values of \alpha & \beta, which is a bit different from the actual paper, but seems to work with the Gaussian distribution well

# Contributors

Prishat Bachhar

Subir Kumar Parida

Yashwant Raghuwanshi
