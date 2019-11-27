# Car Insurance Policy - Inferential Modeling

<p>
    The Car insurance Policy dataset provides a set of attributes and also indicates whether the consumer purchased the insurance policy. This is a business optimisation problem where the problem models a realistic problem of ascertaining the most significant features of the dataset. These features would then be used by the insurance service provider company to provide value added services to a specific segment in the consumer space. Additionally, the indentification of the most significant features will provide a blue print to emphasize on the most important attributes and to de-clutter the problem space.
</p>

<hr />

## Implemenation Methodology

<p>
This problem fits a probablistic model solution which has to be built over a dimensionality reduction. Therefore the approach employed for this problem was to eliminate the insignificant features and then build probablisitic models as a means to cross validate the selection of the selected features.

The step by step method used is as follows:
<ol>
    <li>Getting rid of Zero/nearZeroVariance variables</li>
    <li>Removing features with high perentage of missing values</li>
    <li>Performing detailed Exploratory Data Analysis for all the Features</li>
    <li>Getting rid of pair-wise correlation among the predictors</li>
    <li>Identifying features highly correlated to the response variable</li>
    <li>Wrapper methods</li>
    <li>Cross Validation</li>
    <li>Prediction of Carvan Policies for Customers</li>
    <li>Evaluation of Model Performance</li>
</ol>

The Inferential analysis has been supplmented by graphical data exploration and statisitcal exploration as well. The solution metrics have been visulized in every possible stage which helps reinforce the correctness of the employed method or step. 



The Exploratory Data Anlaysis includes a combination of multiple distribution which help in determining the statistical significance of the features.
<ol>
    <li>Hinged Box plots - Helps in identifing oultiers</li>
    <li>Histograms - the overall distribution of the feature</li>
    <li>Scatter plots - to find out correlation patters between features</li>
</ol>

![doc_image](https://github.com/girish1993/Car-Insurance-analsysis/blob/master/doc_images/img.png)

The jupyter notebook has detailed description and implementation.
</p>