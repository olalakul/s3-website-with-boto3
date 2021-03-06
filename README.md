# S3 Website with boto3

Using boto3 - the ASW SDK for python - to host a static website on Amazon S3. Created during "Intro to Cloud DevOps" Udacity Course.


Jupyter notebook s3_website.ipynb contains the python code, which uses boto3

<img src="pictures/S3-Website.png" alt="Architectural Diagram for Static Website Hosting on S3" width="400"/>

The content of website is stored in wholesale-more-fozen-products directory.
This is a nested directory with files of several different types. 
I created it several year ago, when doing data analysis with R.

#### Why this project

As a Data Scientist, I do care that my projects are deployed and running in production, therefore my interest in Data Engineering and DevOps part. I also care, that business-users have access to insights and advanced visualizations that I produce.

Therefore I make interactive visualizations with Jupyter notebooks. Each Jupyter notebook can easily be converted to HTML file (or HTML file and images), which in turn can constitute static website. I host those websites.

AWS S3 is a perfect opportunity to host everything simple and quickly. Boto3 is AWS SDK for python. I am just starting with boto3 and I love it. No mouse-clicking, just python script.

