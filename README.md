# Big Data Made Easy - Manage, Analyze, & Visualize Data Insights with AWS


Big Data is a hot topic in the world today. From customer experience optimization engines at Netflix to stunningly accurate weather prediction technology on windows, its applications can be found anywhere. Through this project, we aim to demonstrate to viewers a sequential solution to a common problem that every business is facing today: How to use and capitalize on all this available data? This is an important issue to solve, because business insights found through big data can be taken advantage, ultimately leading to better customer experience and more profit among other benefits. An ideal solution should satisfy these requirements:

1.	Storage of big data in an environment that is secure, manageable, scalable, and affordable 
2.	Support for deriving insights from state of the art, easy to use build, train, & deploy machine learning solutions
3.	Visual platform to deliver insights in an easy to understand way

Luckily, there are solutions that tackle these very problems and they do it well. To solve the first problem about storage, AWS's S3 simple storage system is the premier cloud storage and management platform. With S3, secure, manageable, scalable big data storage is only a few clicks away with the added benefit of being offered at an affordable price. For problem number two, once the data is stored, AWS's SageMaker is the ideal candidate to pair with S3 to build, train, and deploy state of the art machine learning solutions. And finally, to visualize, AWS's QuickSight visualization platform offers an easy to understand user interface able to pull insights from multiple data sources available including easy integration with AWS, third party data, spreadsheet data, SaaS data, business to business data, and much more.

In our project, we leveraged the power of S3, SageMaker, and Quicksight, to demonstrate one of the potential use case of these tools. We utilized a Kaggle dataset for Amazon product reviews, which is a file that contains around 7.5 million rows of review data, starting from 1998 to 2014. Using this dataset, we first did a spam detection to identify which are the real reviews and which are the fake ones. Afterwards, we used LDA technique to retrieve common words in each of the topics. In so doing, we can see what the customers are saying about a specific product. Lastly, we used QuickSight to build a dashboard for intuitive visualization. In the dashboard, we can see clearly identify the rating trends of a product, the words that are commonly seen, etc.
Below are a flyer and a short video describing the benefits of this solution along with providing more detailed information about our analysis.



**Flyer Link:**
[Flyer - Copy.pdf](https://github.com/Koller08/big-data-sector-analysis/files/6411392/Flyer.-.Copy.pdf)


**Video Link (Also on Flyer):**
https://www.youtube.com/watch?v=Ol0SQHXisZU


**Check out these links for more information below:**

- [Amazon S3](https://aws.amazon.com/s3/)

- [Amazon SageMaker](https://aws.amazon.com/sagemaker/)

- [Amazon QuickSight](https://aws.amazon.com/quicksight/)




*This project repository is created in partial fulfillment of the requirements for the Big Data Analytics course offered by the Master of Science in Business Analytics program at the Carlson School of Management, University of Minnesota.*
