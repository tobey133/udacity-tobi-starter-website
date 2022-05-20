## Travel Blog 

This project is to show how to host a static website with s3 and also access it with cloudfront too 

wbesite url: http://tobiainaudacityproject.s3-website.us-east-2.amazonaws.com

link to my cloudfront: https://d2p6l802lnrd0e.cloudfront.net

link to screenshot of steps followed: https://drive.google.com/drive/folders/183ZilFqGRpdc7RKWvR8Yf9KmUn7d4uUD?usp=sharing

 create an s3 bucket

The S3 bucket is visible in the AWS Management console.

![s3 bucket created](https://user-images.githubusercontent.com/54315781/168576220-42ccca06-1b9a-4315-af41-ca10d331c1d0.jpg)

Screenshot showing all website files uploaded to the S3 bucket 
[s3 bucket content](https://user-images.githubusercontent.com/54315781/168576225-3e28bebf-10b5-4053-8c0f-d65a843d9d68.jpg)

The S3 bucket is configured to support static website hosting.
![configuration to support static website hosting](https://user-images.githubusercontent.com/54315781/169029661-16677e1a-f5cf-4484-a206-25bb5f50e986.jpg)

The bucket should allow public access. The S3 bucket has an IAM bucket policy that makes the bucket contents publicly accessible.
 ![s3 bucket iam policy](https://user-images.githubusercontent.com/54315781/168576241-407bc1bf-9bfe-4530-9e25-aa1f7377fd74.jpg)
 
CloudFront has been enabled to retrieve and distribute website files.
![cloudfront distrubtions](https://user-images.githubusercontent.com/54315781/168576253-d27aab2e-543e-484e-861e-3fd5956f6d47.jpg)

11) Website is accessible publicly through both the endpoints.

link to my website cloudfront: https://d2p6l802lnrd0e.cloudfront.net
wbesite s3 url: http://tobiainaudacityproject.s3-website.us-east-2.amazonaws.com
link to screenshot of steps followed: https://drive.google.com/drive/folders/183ZilFqGRpdc7RKWvR8Yf9KmUn7d4uUD?usp=sharing



![configure s3](https://user-images.githubusercontent.com/54315781/168576230-2f76bda6-61f0-426f-b2ad-80f59dc549bf.jpg)




