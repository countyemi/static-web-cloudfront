# static-web-cloudfront
Host a static website on AWS S3 with Cloudfront
1. Choose S3 bucket service

![1](https://github.com/countyemi/static-web-cloudfront/assets/11930705/1658c7e0-40cd-471b-9981-609c043494e6)

2. Choose bucket name


![2](https://github.com/countyemi/static-web-cloudfront/assets/11930705/66399af5-fb03-4255-ab5b-0ebe3136eed3)

3. Create bucket
   ![4](https://github.com/countyemi/static-web-cloudfront/assets/11930705/5ec0bd5e-e135-4f11-8933-d10ad4b37ca4)


![5](https://github.com/countyemi/static-web-cloudfront/assets/11930705/fa96792a-f3e1-4cfe-accc-63d3cd7b26e9)


4. Set up cloudfront
   
![CF1](https://github.com/countyemi/static-web-cloudfront/assets/11930705/5ea061ee-35e2-4f8f-8f8c-d069992649d8)

5. Select origin, name, origin access control and create new origin access control

![CF2](https://github.com/countyemi/static-web-cloudfront/assets/11930705/8c96b994-15da-4bcc-ba3b-45d40eae6391)


6. Choose name for the origin access control and create
![CF3](https://github.com/countyemi/static-web-cloudfront/assets/11930705/c79ebc95-a457-4f2f-841e-b28a7bdbeffe)

   

7. Give default root object and distribution locations
   ![CF4](https://github.com/countyemi/static-web-cloudfront/assets/11930705/aafb5bbb-ca6b-46f3-9b32-eac695127670)
8. create distribution
9. Copy S3 bucket policy
![CF5](https://github.com/countyemi/static-web-cloudfront/assets/11930705/14a90f76-d02a-4ac1-b8f6-b57eb522f46c)

10. Update bucket policy
   ![UPDATE BUCKET POLICY](https://github.com/countyemi/static-web-cloudfront/assets/11930705/3327499b-ae9d-48b8-b3e7-010a549d5f9b)

11. Copy distribution domain name
![CF6](https://github.com/countyemi/static-web-cloudfront/assets/11930705/995c8b94-badd-4f7a-8f56-b7fec4db3433)


12. Access website using distribution domain

![CFFF](https://github.com/countyemi/static-web-cloudfront/assets/11930705/74420aef-5c08-47c9-9941-987ff20b0cb7)

    

