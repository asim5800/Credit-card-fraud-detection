# Credit-card-fraud-detection

Let's imagine we're deep learning scientists working for a bank and we are given a data set that contains information of customers from this bank applying for an advanced credit card. Informations are the data that customers had to provide when filling the application form. And our mission, is to detect potential fraud within these applications. So that means that by the end of the mission,we have to give the explicit list of the customers who potentially cheated.

What we're gonna do is unsupervised deep learning which means that we will identify some patterns in a high dimensional data sets full of nonlinear relationships & one of these patterns will be the potential fraud. For this purpose we'll use Self Organising Maps.

What is the core purpose of SOMs?
The short answer would be reducing dimensionality. The example below of a SOM comes from a paper discussing an amazingly interesting application of self-organizing maps in astronomy.

<p align="center">
  <img width="460" height="300" src="https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/66_blog_image_3.png">
</p>

The example shows a complex data set consisting of a massive amount of columns and dimensions and demonstrates how that data set's dimensionality can be reduced.

So, instead of having to deal with hundreds of rows and columns (because who would want that!), the data is processed into a simplified map; that's what we call a self-organizing map.

The map provides you with a two-dimensional representation of the exact same data set; one that is easier to read.

The data set is taken from the UCI Machine Learning Repository, Statlog Australian Credit Approval Data Set.

All attribute names and values has been changed to meaningless symbols to protect confidentiality of the data. This problem even more complex and difficult to solve for human, indeed when we see the data set, we feel totally incapable of detecting any fraud.

So we clearly need a deep learning model to find the cheaters.



<p align="center">
  <img width="460" height="300" src="https://drive.google.com/file/d/1lj9qU3uDqpoN8woVfH7dSwB5v8N1jhhz/view?usp=sharing">
</p>
