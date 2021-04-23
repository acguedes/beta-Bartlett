# Bartlett-corrected tests for varying precision beta regressions with application to environmental biometrics
The computer code can be used to perform empirical application of the article.

# Authors
Ana C. Guedes, Francisco Cribari-Neto, Patrı́cia L. Espinheira

# Programming language
R statistical computing environment.

# Description of files 
## Data analysis
The programs can be used to replicate some of the empirical results presented  in the fourth section of the article. 

#### Atheists data
Data on the fifty countries with the largest prevalence of atheists (n = 50) from Cribari-Neto and Souza (2013).

#### Application 1 
The code can be used to test H_0: \beta_4 = 0 in Model 2. The following test statistics are computed: the likelihood 
ratio test statistic ($\omega$), the third Bartlett-corrected test statistic ($\omega_{b3}$), and the first alternative 
modified test statistic ($\omega_{a1}$). The p-values of such tests are also computed.

#### Application 2
The code can be used to test H_0: \beta_5 = 0 in Model 2. The following test statistics are computed: the likelihood 
ratio test statistic ($\omega$), the third Bartlett-corrected test statistic ($\omega_{b3}$), and the first alternative 
modified test statistic ($\omega_{a1}$). The p-values of such tests are also computed. 

#### Application 3
The code can be used to test H_0: \beta_4 = \beta_5 = 0 in Model 2. The following test statistics are computed: the likelihood 
ratio test statistic ($\omega$), the third Bartlett-corrected test statistic ($\omega_{b3}$), and the first alternative modified 
test statistic ($\omega_{a1}$). The p-values of such tests are also computed. 

#### Reduced Model 
The program can be used to calculate the parameter estimates and asymptotic standard errors for the reduced model and also 
the fitted model quality measures.

## Bartlett correction factor 
#### Beta Bartlett
The function returns the epsilon_k of Bartlett's correction. This function uses the general matrix expression to obtain the bartlett 
correction factor presented in Cordeiro (1993).

# Files 
#### Atheists data
* atheists-data.txt
#### Application 1 
* application1.r
#### Application 2 
* application2.r
#### Application 3 
* application3.r
#### Reduced Model 
* application_reducedmodel.r
#### Beta Bartlett
* beta_bartlett.r

# Contact
To questions regarding the computer code, please contact with
Cristina Guedes (crisguedespereira at gmail [dots] com)
