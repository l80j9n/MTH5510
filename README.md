java cMTH5510: QRM - Exercises Set 2
Due date: August 12, 2024;12:00pm;
Analysis the output of the Matlab code is mandatory. I am not interested just to the Matlab code.
Hand in stapled hardcopy at the beginning of the tutorial session
Note: You might want to use Matlab for this exercise; adequately report and comment on your
results (For a quick introduction to Matlab visit http://www.mathworks.com/access/helpdesk/
help/pdf_doc/matlab/getstart.pdf)
Exercise I: This question deals with a portfolio of five stocks. At time t, the values of the stocks
are S1,t = 100, S2,t = 50, S3,t = 25, S4,t = 75, and S5,t = 150. The portfolio consists of 1 share
of S1, 3 shares of S2, 5 shares of S3, 2 shares of S4, and 4 shares of S5. These risk factors are
logarithmic prices and the factor changes have mean zero and standard deviations 10?3, 2 · 10?3,
3 · 10?3, 1.5 · 10?3, and 2.5 · 10?3, respectively. The risk factors are independent.
1. Compute VaRα, VaR
mean
α , and ESα using Monte Carlo with 10,000 simulations. Do this for
α = {0.90, 0.91, . . . , 0.99}. Also use the following distributions for the risk factor changes:
 For each i ∈ {1, 2, 3, 4, 5}, Xi,t+δ ～ t(3, μ, σ) for appropriate values of μ and σ
 For each i ∈ {1, 2, 3, 4, 5}, Xi,t+δ ～ t(10, μ, σ) for appropriate values of μ and σ
For each i ∈ {1, 2, 3, 4, 5}, Xi,t+δ ～ t(50, μ, σ) for appropriate values of μ and σ
 For each i ∈ {1, 2, 3, 4, 5}, Xi,t+δ ～ N (μ, σ2)
P代 写MTH5510、Matlab
代做程序编程语言lot the results.
2. Comment on the following:
 The value of VaRα compared to VaRmeanα
 The value of VaRα and ESα as compared between the four distributions. Are the results
what you expected?
Exercise II: This question deals with delta hedged call option. The following are the Black-
Scholes parameters for a European call option at time t = 0:
T = 0.5
rt = 0.05
σt = 0.2
St = 100
K = 100.
1
The portfolio consists of long position on the call option, and the corresponding position in the
stock which makes the portfolio delta neutral. Let ? = 1day, Z1 = log(S), and Z2 = σ (r
will be considered in this problem). The risk factor changes are normally distributed with mean
zero. Their standard deviations over one day are 10?3 and 10?4 and their correlation is ?0.5.
(a) Compute V aRα, V aR
mean
α , and ESα for α = 0.95 and α = 0.99 using the following
methods:
 Monte Carlo full revaluation with 10,000 simulations
 Monte Carlo on the linearized loss with 10,000 simulations
 Variance-covariance method
Do not neglect the time derivative in any linearizion in this question.
Exercise III: Let L have the Student t distribution with ν degree of freedom. Derive the
formula
ESα(L) =
(
gν(t
?1
ν (α))
1? α
)(
ν + (t?1ν (α))2
ν ? 1
)
.
You will need to look up the probability density function of the distribution at hand.
2

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
