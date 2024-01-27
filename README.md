# Static-Website-hosting-on-AWS-using-s3
Hello Everyone. In this first project of mine I have tried this simple project of hosting a static website using AWS. It involves the usage of Amazon Simple Storage Service (Amazon S3).
# What is the static website?
A static website is one that appears in a web browser precisely as it is stored. It is often referred to as a flat or motionless page. It consists of HTML-coded web pages with static content that are kept on a web server. It remains constant, unchanging, or "static" for each and every website visitor.
# What is Amazon Simple Storage Service (Amazon S3)?
The object storage service Amazon Simple Storage Service (Amazon S3) provides performance, security, scalability, and data availability that are among the best in the business. To store and safeguard any volume of data for a variety of use cases, including data lakes, websites, mobile applications, backup and restore, archiving, business applications, IoT devices, and big data analytics, customers of all sizes and sectors can utilize Amazon S3. It can optimize, arrange, and configure access to your data using the administration tools that Amazon S3 offers to satisfy your unique organizational, business, and compliance needs.

![advantages-of-aws-s3](https://github.com/shreyajaiswal04/Static-Website-hosting-on-AWS-using-s3/assets/120746269/eb7d6a91-8905-40a9-9463-ee3638e5b6a0)

# Steps to host a static website using Amazon S3.
1-Go to AWS Management Console . From services select S3.
2-Select Buckets and click on 'Create Bucket'.
3-Select region. And give a name must be unique and shouldn't contain uppercase alphabets.
4-Grant public access by unchecking the option.
5-Click on 'Create Bucket'
6-Now click on the 'Bucket name' and from objects click on upload to upload theb files.
7-Upload the file.I uploaded HTML file with an image.
8-Go to properties ans enable the static website hosting option
9-Go to permission and write the required code in Bucket Policy.
10-A link will be visible now.Click on that to launch a website.
![project_result](https://github.com/shreyajaiswal04/Static-Website-hosting-on-AWS-using-s3/assets/120746269/e709cbe7-6d5f-44b6-94d3-7ab54acdc79d)

The above image showa the launched website.
# Codes Used:
1-HTML file.

![Screenshot (3542)](https://github.com/shreyajaiswal04/Static-Website-hosting-on-AWS-using-s3/assets/120746269/b68ded57-479d-4f58-bfde-5accfb2d82ba)

2-Bucket Policy code.

![Screenshot (3541)](https://github.com/shreyajaiswal04/Static-Website-hosting-on-AWS-using-s3/assets/120746269/2c0564bc-5ea7-4a0b-b3c0-c7981f0f572e)


# Benefits:
1- Scalability and availability.

2- Encryption of data in transit.

# Conclusion
Static webpages can be hosted on Amazon Simple Storage Service (Amazon S3) without a web server. The website costs a fraction of what a conventional web server would at a far higher performance and scalability. Amazon S3 is cloud storage that offers safe, robust, and extremely scalable object storage. You may save and retrieve any volume of data from any location on the internet with a straightforward web services interface.



