# Santander-Value-Prediction-Challenge
This is my solution of Santander value prediction challengeon Kaggle

 <H1>PLAN OF ATTACK</h1>
 <ul>
 <ol>
 <li><h5>IMPORTING THE DATA</h5></li>
 <li><h5>CLEANING AND ANALYSIS OF THE DATA</h5></li>
 <li><h5>SOME DATA VISUALISATION</h5></li>
 <li><h5>SPLITTING THE DATA</h5></li>
 <li><h5>BUILDING THE MODEL</h5></li>
 </ol>
 
</ul>
<H2>DESCRIPTION ABOUT DATA</H2>
 <p><h5>This dataset contains anonymised data with lots of zeroes with some missing datapoints.It has large number of features(4.9k) <br > with anonymised name.
 In such situation extensive feature engineering is required.  
</h5> </p>
<H2>Curse of dimensionality</H2>
<p><h5>"when the dimensionality increases, the volume of the space increases so fast that the available data become sparse. This sparsity is problematic for any method that requires statistical significance.<br>
 In order to obtain a statistically sound and reliable result, the amount of data needed to support the result often grows exponentially with the dimensionality. Also, organizing and searching data often relies on detecting areas where objects form groups with similar properties; in high dimensional data, however, all objects appear to be sparse and dissimilar in many ways, which prevents common data organization strategies from being efficient. "<h5></p>

<H2>SOLUTION TO THE PROBLEM</H2>
<p>Dimention reduction through different techniques available like PCA, LDA ,T-SNE and auto-Encoder.<br>
</p>

<H2>TECHNIQUES USED</H2>
<ul>
<ol>
<li><h5>DIMENTION REDUCTION USING: AUTOENCODER + PCA</h5></li>
<li><h5>DIMENTION REDUCTION USING: AUTOENCODER + KernnelPca</h5></li>
 <li><h5>ONLY PCA</h5></li>
</ol>
</ul>
<H2>ALGORITHMS USED</H2>
<ul>
<ol>
 <li><h5> LINEAR REGRESSTION </h5></li>
 <li><h5> DECISIONTREE </h5></li>
 <li><h5> RANDOMFOREST </h5></li>
 <li><h5> XGBOOST </h5></li>
 </ol>
 </ul>

<H2>RESULT</H2>


<table style="width:100%">
  <tr>
    <th>ALGORITHM</th>
    <th>LINEAR_REGRESSION</th> 
    <th>RANDOMFOREST</th>
    <th>DECISIONTREE</th>
    <TH>XGBOOST</TH>
  </tr>
  <tr>
    <td>AUTOENCODER + PCA</td>
    <td>2.8860584752682324e+2</td>
    <td>3.0088379732492547</td>
	<td>5.3416815129317925</td>
    <td>0.9184666846350971</td>

  </tr>
  <tr>
    <td>PCA</td>
    <td>2.8860584752682324e+23</td>
    <td>3.0088379732492547</td>
    <td>5.3416815129317925</td>
    <td>0.9184666846350971</td>

  </tr>
  <tr>
    <td>KERNELPCA+AUTOENCODER</td>
    <td>1.071997067379852</td>
    <td>3.0088379732492547</td>
    <td>2.1897963692832154</td>
    <td>1.0717463743702915</td>

  </tr>
  <TR>
   <td>NULL</td>
  <td>5.215524806023528e+21</td>
  <td>0.15023345767896787</td>
  <td>1.7761094074203194e-09</td>
  <td>0.6983542408556609</td>

  
  
  
  </TR>
</table>




























