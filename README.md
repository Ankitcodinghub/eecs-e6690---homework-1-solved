# eecs-e6690---homework-1-solved
**TO GET THIS SOLUTION VISIT:** [EECS-E6690 – Homework 1 Solved](https://www.ankitcodinghub.com/product/eecs-e6690-homework-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120225&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EECS-E6690 - Homework 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
E6690: Statistical Learning for Bio &amp; Info Systems

P1. Let

and .

Show that:

(b) (2pt) If X1,X2,…,Xn are independent and identically distributed (i.i.d.), the S2 is an unbiased estimator of σ2, i.e., ES2 = σ2

In the following, in addition to the above, assume that Xi-s have normal/Gaussian distribution N(µ,σ2).

(c) (3pt) Show (prove) that X¯ is independent of Xi − X¯, i = 1,2,…,n.

(Hint: Both X¯ and Xi − X¯ are normal.)

(d) (3pt) Show (prove) that the sample mean, X¯, is independent of the sample variance, S2.

P3. (20pt; each bullet 2pt) Create some simulated data and fit simple linear regression models to it. Make sure to use set.seed(1) prior to starting part (a) to ensure consistent results.

(a) Using the rnorm() function, create a vector, x, containing 100 observations drawn from a N(0,1) distribution. This represents a feature, X.

(b) Using the rnorm() function, create a vector, eps, containing 100 observations drawn from a N(0,0.25) distribution.

(c) Using x and eps, generate a vector y according to the model

What is the length of the vector y? What are the values of β0 and β1 in this linear model?

(d) Create a scatterplot displaying the relationship between x and y. Comment on what you observe.

(e) Fit a least squares linear model to predict y using x. Comment on the model obtained. How do βˆ0 and βˆ1 compare to β0 and β1?

(f) Display the least squares line on the scatterplot obtained in (d). Draw the population regression line on the plot, in a different color. Use the legend() command to create an appropriate legend.

(g) Now fit a polynomial regression model that predicts y using x and x2. Is there evidence that the quadratic term improves the model fit? Explain your answer.

(h) Repeat (a)-(f) after modifying the data generation process in such a way that there is less noise in the data. The model in (c) should remain the same. You can do this by decreasing the variance of the normal distribution used to generate the error term in (b). Describe your results.

(i) Repeat (a) − (f) after modifying the data generation process in such a way that there is more noise in the data. The model in (c) should remain the same. You can do this by increasing the variance of the normal distribution used to generate the error term in (b). Describe your results.

(j) What are the confidence intervals for β0 and β1 based on the original data set, the noisier data set, and the less noisy data set? Comment on your results. (You could use the confint() function.)

P4. (10pt) Using R and Advertising data set, find 92% confidence intervals for β0 and β1 for three singlefeature linear regressions of Sales versus Newspaper, TV and Radio, respectively. Then, create a scatterplot for each of them with the 92% confidence interval lines, i.e., draw the lines that correspond to the ends of confidence intervals for (β0,β1). The answer should include the R code and graphs.

P5. Consider the Auto data set:

(a) (5pt) Produce a scatterplot matrix which includes all of the pairs of variables in the data set.

(b) (5pt) Compute the matrix of correlations between the variables using the function cor(). You will need to exclude the name variable, which is qualitative.

(c) (5pt) Use the lm() function to perform a multiple linear regression with mpg as the response and all other variables except name as the predictors. Use the summary() function to print the results. Comment on the output. For instance:

i. Is there a relationship between the predictors and the response?

ii. Which predictors appear to have a statistically significant relationship to the response?

iii. What does the coefficient for the year variable suggest?

√

(d) (5pt) Try a few different transformations of the variables, such as log(X), X, X2. Comment on your findings.

P6. (10pt) A data set has n = 20,

, and .

Calculate βˆ0, βˆ1 and σˆ2. What is the fitted value when x = 0.5? Compute R2.

P7. (10pt) The multiple linear regression model

y = β0 + β1×1 + β2×2 + β3×3 + β4×4 + β5×5 + β6×6

is fitted to a data set of n = 45 observations. The total sum of squares is TSS = 11.62, and the residual sum of squares is RSS = 8.95. What is the p-value for the null hypothesis

H0 : β1 = β2 = β3 = β4 = β5 = β6 = 0 ?

Extra Credit

Under normal assumptions we can compute the distributions of a lot of quantities explicitly.

E1. (5pt) Chi-squared distribution. Let X1,X2,…,Xn be independent standard normal random variables and recall that Chi-squared random variable with n degrees of freedom is defined as .

Prove that the density of χ2n is given by

,

where Γ(x) is the gamma function. (Hint: Prove first for n = 1,2, and then use the mathematical induction.) E2. (5pt) Let X1,X2,…,Xn be independent normal random variables N(µ,σ2). Prove that

,

d

where = stands for equality in distribution.

(Hint: Derive the moment generating function of χ2n and use problem P1.(a) and (d).) E3. (5pt) Student’s t distribution. Let tn be student’s t variable, defined as

,

where Z ∼ N(0,1). Prove that tn has the density

,

where2 √Γ(x) is the gamma function. Show that for large values of n, fn(t) is approximately normal, fn(t) ≈

e−t / 2π. (Hint: First show that the conditional density (distribution) of tn given is normal with mean 0 and variance pn/x. Then, use problem E1. to integrate this conditional density.)

E4. (5pt) F (Fisher) distribution. Let U and V be two independent Chi-squared random variables with degrees of freedom n1 and n2, and define the random variable, F ≡ F(n1,n2), as

.

Show that the density of F is given by

.

(Hint: Compute first the distribution of F given V .)
