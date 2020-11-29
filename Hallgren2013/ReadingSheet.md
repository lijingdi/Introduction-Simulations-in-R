# Conducting Simulation Studies in the R Programming Environment - Reading Sheet

***
[Hallgren A. K. 2013. Conducting simulation studies in the R programming environment. Tutor Quant Methods Psychol. ; 9(2): 43–60.](https://doi.org/10.20982/tqmp.09.2.p043) 

***

Hallgren (2014) describes the benefits of using simulations and provides examples of applications.

1)	Please list all the words that you do not know/concepts you do not understand in this paper (except mediation, branching, zero-inflation, ceiling effect, structural equation models, social network exponential random graph).  
    *  SobelZ
    *  
    *  

2) In your own words, describe which steps are common to all sorts of simulations. Illustrate with simple examples rather than, or in addition to, using terms such as assumptions and parameters.    
**1)**   set the assumptions and specify the parameters of a dataset
**2)**   generated the dataset using functions like sample/rnorm, according to the assumptions and parameters set in step1 
**3)**   statistical analysis on the generated dataset and obtain parameter estimates which are of interest
**4)**   repeat step2 and step3 for many times: statistical analysis on newly generated dataset each time, in order to obtain an empirical distribution of parameter estimates
**5)**   modify the assumptions/paramaters in step1 for the dataset and repeat step2-4 (to increase the robustness of the simulation analysis)
**6)**   the obtained distribution of parameter estimates from these simulated datasets are analyzed to evaluate the question of interest



3)	In your own words, describe the 3 types of applications for simulations covered by the author.  
**1)**   answer a novel question about statistical analysis, eg. evaluate the robustness of a statistical procedures like mediation analysis
**2)**   estimate statistical power of Sobel test
**3)**   obtain confidence intervals of parameters through bootstrapping

4)	Describe, with your own words and/or examples, the 4 limitations to simulations mentioned by the author.  
**1)**   real-world data is more dirty than simulated data and the degree to which these aspects should be modeled into the data may be unknown and thus at times difficult to incorporate in a realistic manner
**2)**   it’s unrealistic and typically impossible to pinpoint the exact parameter values that apply in the simulation analysis 
**3)**   simulation analysis might be computationally intensive and time-consuming 
**4)**   not all statistical questions require simulations, and some can be solved by mathematical derivations
