# AWS Static Portfolio Website

This project is my first hands-on AWS deployment after completing the AWS Cloud Practitioner.

I designed and deployed a responsive personal portfolio using Amazon S3 and CloudFront to understand real-world static website hosting in the cloud.

---

## Live Demo

🔗 CloudFront URL: d3vkh3x0hsrjoi.cloudfront.net

---

## 🧭 Architecture

Browser → CloudFront → Amazon S3 → Static Files

This setup improves performance, scalability, and security compared to hosting directly from S3.

---

## AWS Services Used

- Amazon S3 (static website hosting)  
- Amazon CloudFront (CDN)  
- AWS IAM (access control)  
- AWS Certificate Manager (HTTPS readiness)  
- Amazon Route 53 (custom domain readiness)

---

## Key Features

- Responsive mobile-first design  
- Global content delivery via CloudFront  
- Secure public read access via bucket policy  
- Cost-efficient static hosting  
- Clean professional UI  

---

## Local Development

To run locally:

- Open project in VS Code  
- Right-click `index.html`  
- Select Open with Live Server

---

##  What I Learned

- How S3 static hosting works  
- Difference between S3 endpoints  
- How CloudFront distributions are configured  
- Writing secure bucket policies  
- Importance of testing before deployment  

---

## Future Improvements

- Serverless contact form (Lambda + API Gateway)  
- Custom domain with Route 53  
- CloudWatch monitoring  
- CI/CD pipeline

---

## Author

**Ramsey Agi**  
AWS Cloud Practitioner → Future Cloud Engineer
