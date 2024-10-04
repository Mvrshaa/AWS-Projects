# Static Website Hosting on Amazon S3

This project demonstrates how to deploy a static website using **Amazon S3**. The project covers the essential steps to create an S3 bucket, upload static files, configure the bucket for static website hosting, and make the website publicly accessible.

By following this project, you’ll gain hands-on experience with **Amazon S3**, one of the foundational AWS services, and learn how to leverage it for simple yet powerful website hosting.


## Features

- **Static Website Hosting**: Host HTML, CSS, and JavaScript files on Amazon S3, making them accessible via a public URL. 

- **Simple Permissions Setup**: Learn how to configure bucket policies to allow public access to your website.


### Steps 

1. **Create an S3 Bucket**:
   - Log in to the AWS Console and navigate to the S3 service.
   - Create a new bucket with a unique name and uncheck "Block all public access" to ensure the website is accessible to users.

2. **Upload Your Website Files**:
   - Upload your HTML, CSS, and JavaScript files to the S3 bucket. In our case, we uploaded our static website files (index.html and error.html).

3. **Configure Static Website Hosting**:
   - Enable static website hosting in the S3 bucket's properties.
   - Set `index.html` as the default entry point for your website.

4. **Set Permissions**:
   - Edit the bucket policy to allow public access to your site. This step ensures that visitors can view your site without restrictions.

5. **Access the Website**:
   - Use the website endpoint URL provided in the S3 bucket properties to access your live static website.


For more detailed instructions, check out the full report [here](https://medium.com/@mvrshaa/creating-a-static-website-using-amazon-s3-dca7dda0c500).
