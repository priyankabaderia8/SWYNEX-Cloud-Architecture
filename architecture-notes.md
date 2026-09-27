# Architecture Notes 

## 1. Frontend
- User accesses website via browser
- Hosted on Vercel / AWS Amplify

## 2. Backend 
- API Gateway + AWS Lambda handles logic

## 3. Database 
- AWS RDS / DynamoDB for storage

## 4. FLow
user -> Frontend -> AOI Gateway -> Backend -> Database -> Response to User

## 5. Security & Monitoring 
-HTTPS, Authentication 
-CloudWatch for logs and Monitoring 
