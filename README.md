# H-M-Personalized-Fashion-Recommendations
This is a Kaggle competition, H&amp;M Group invites  to develop product recommendations based on data from previous transactions, as well as from customer and product meta data. The available meta data spans from simple data, such as garment type and customer age, to text data from product descriptions, to image data from garment images.

## Terminologies
There are certain terminologies which needs to be understood before moving forward.

### Apache Spark: 
Apache Spark is an open-source distributed general-purpose cluster-computing framework.It can be used with Hadoop too.

### Collaborative filtering: 
Collaborative filtering is a method of making automatic predictions (filtering) about the interests of a user by collecting preferences or taste information from many users. Consider example if a person A likes item 1, 2, 3 and B like 2,3,4 then they have similar interests and A should like item 4 and B should like item 1.

### Alternating least square(ALS) matrix factorization: 
The idea is basically to take a large (or potentially huge) matrix and factor it into some smaller representation of the original matrix through alternating least squares. We end up with two or more lower dimensional matrices whose product equals the original one.ALS comes inbuilt in Apache Spark.

### PySpark: 
PySpark is the collaboration of Apache Spark and Python. PySpark is the Python API for Spark.
