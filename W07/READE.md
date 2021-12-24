#Information
Hard Deadline: 	Mon 25 May 2015 7:00 AM PDT  
Duration: Untimed  
Attempts: 100  

#Question 1
Which of the following options is not considered a stochastic restoration approach?

**[-]** Wiener filter  
**[X]** Constrained least-squares filter  
**[-]** Maximum likelihood estimation  
**[-]** Maximum a posteriori estimation  

#Question 2
Which of the following describes the "orthogonality principle" of Wiener filter? Let f(i,j), y(i,j), and f^(i,j) denote the original, degraded, and restored signal, respectively.

**[-]** E[f(i,j)−f&#770;(i,j)]=0  
**[-]** E[f(i,j)−y(i,j)]=0  
**[X]** E[(f(i,j)−f&#770;(i,j))y<sup>∗</sup>(k,l)]=0   
**[-]** E[(f(i,j)−y(i,j))f&#770;<sup>∗</sup>(k,l)]=0    


#Question 3
(True/False) In general, the constrained least-squares restoration filter has better performance than the Wiener restoration filter.

**[-]** True  
**[X]** False  


#Question 4
In the Bayesian formulation, if p(f) denotes the image prior distribution, p(y|f) denotes the likelihood, where y denotes the noisy and blurred image, then p(f|y) denotes

**[-]** the joint distribution  
**[-]** the likelihood  
**[X]** the posterior distribution  
**[-]** the prior distribution  


#Question 5
Which of the following statements about the Bayesian formulation of image restoration is (are) correct? Check all that apply.

**[-]** Noise must have Gaussian distribution  
**[-]** Maximum likelihood estimation maximizes the posterior distribution  
**[-]** Maximum a posteriori estimation always results in closed-form solutions  
**[-]** The total variation prior promotes piecewise smooth restored images  


#Question 6
Which of the following options represent image restoration problems? Check all that apply.

**[-]** Image super-resolution
**[-]** Defocusing
**[-]** Pansharpening
**[-]** Video compression
**[-]** Contrast stretching


#Question 7
In this problem, you will implement the Constrained Least Squares (CLS) filter and examine its performance when the regularization parameter is set at different values. You will be provided with the original image and a set of MATLAB files. Follow the instructions below to finish this problem.

1. Download the original image and the MATLAB code from here. Place the original image and all the provided MATLAB files in the same directory.

2. The file "wrapper.m" is the entry or the "main" code. It loads the original image, applies a motion blur to it, and degrades the image by adding noise. The 17th line in "wrapper.m" sets the value of the regularization parameter "alpha".

3. The MATLAB file "cls_restoration.m" has an incomplete implementation of the CLS filter. You need to un-comment line 24 in "cls_restoration.m" and complete the implementation of the CLS filter.

4. After you complete the implementation of the CLS filter, you should run "wrapper.m" with different values of alpha. Specifically, we ask you to try the following values of alpha: {0.0001, 0.001, 0.01, 0.1, 1, 10, 100}. For each value of alpha, we ask you to compute the Improvement in SNR (ISNR). Note that the computation of ISNR involves there images: the original image, the blurred and noisy image, and the restored image. After you obtain the ISNR values, enter in the box below the largest ISNR value. Enter the number with at least two decimal points.

**[-]** ?
