# AWS Static Portfolio Website

This project is my first hands-on AWS deployment after completing the AWS Cloud Practitioner.

I designed and deployed a responsive personal portfolio using Amazon S3 and CloudFront to understand real-world static website hosting in the cloud.

---

## Live Demo

🔗 CloudFront URL: d3vkh3x0hsrjoi.cloudfront.net

---

## Live Website
<img width="1440" height="860" alt="Screenshot 2026-02-19 at 6 55 54 PM" src="https://github.com/user-attachments/assets/cca1f328-009c-42cc-b421-71a89f0b66a5" />

## S3 bucket
<img width="1440" height="729" alt="Screenshot 2026-02-19 at 6 48 09 PM" src="https://github.com/user-attachments/assets/ed698315-fdcb-435d-a211-87f2a6d0eb28" />

## Static Hosting Enabled
<img width="1440" height="471" alt="Screenshot 2026-02-19 at 6 52 50 PM" src="https://github.com/user-attachments/assets/9ac16dec-bdc0-4156-b058-10a896b94299" />

## CloudFront Distribution
<img width="1440" height="727" alt="Screenshot 2026-02-19 at 6 45 52 PM" src="https://github.com/user-attachments/assets/cbabeb4b-f6e4-4749-b5ca-45ae019eac47" />

## Architecture

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
