* **Amazon CloudFront** is a **fast content delivery network (CDN) service** that **securely delivers data, videos, applications, and APIs to customers globally with low latency, high transfer speeds**, all within a **developer-friendly environment** , whereas **Amazon Simple Storage Service (Amazon S3)** is an **object storage service** that offers **industry-leading scalability, data availability, security, and performance**
* **Benefits of setting up an Amazon CloudFront content delivery network (CDN) distribution with Amazon S3** include:
1) **Rapid data transfer speeds**
2) **Improved security and performance** 
3) **Cost-effective data transfers**
* **Steps to set up CloudFront CDN distribution for Amazon S3**:
1) Go to the **AWS Console**, **login** and select **Amazon S3** from the **service list**
2) Create an Amazon S3 bucket by selecting **Create bucket**, then specify a **DNS-complaint bucket name** and further select the **region** where we want our bucket to be located.
3) Go to **CloudFront** from the **Networking &amp; Content Delivery** section of the AWS console service list then create a new web distribution by clicking on **Create Distribution**
4) Enter **distribution settings**
5) Configure **origin**
6) Configure **Origin Access Identity**
7) Configure **default cache behavior**
8) Configure our **TTLs**
9) Configure additional features like **smooth streaming**, **restrict viewer access** etc.                                                                                                                                                                     
then **save**... Once saved, we can review the settings and even add some additional origins and multiple cache behaviors like **create customer error response**, **enable geo-restrictions** (from restrictions tab), **apply custom tags** (from tags tab) etc.
10) **Test our CloudFront distribution**: copy the domain and paste it into the browser to see our distribution in action
