Deploy Static Website on AWS

In this project, you will deploy a static website to AWS using S3, CloudFront, and IAM.

The files included are: 

index.html - The Index document for the website.
/img - The background image file for the website.
/vendor - Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function.
/css - CSS files for the website.

Succesfully deployed out static travel blog page on cloudfront and s3 bucket


S3 Bucket Name: dhruv-staticwebsite1
we have gone for a secure approach (CloudFront with Origin Access Control), our S3 bucket is completely locked down and private to the outside world. The S3 Object URL will always throw an "Access Denied" error if we try to visit it directly in our browser.

CloudFront URL: d1umvvygp0vz6c.cloudfront.net
 and via https://d1umvvygp0vz6c.cloudfront.net/index.html  both these urls are comppletely accessible

S3 Bucket Created: 