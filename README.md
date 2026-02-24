# aws-s3-static-website
Production-ready static website deployment using Amazon S3, CloudFront, OAC, and WAF with private bucket security.

# 🌸 Flower Nest - Static Website Hosting using AWS

This project demonstrates secure static website hosting on AWS using Amazon S3 and CloudFront.

The S3 bucket is configured as private, and access is restricted using CloudFront Origin Access Control (OAC). AWS WAF is enabled for additional protection.

## 🚀 Live Website
https://d2a4qij1prxls4.cloudfront.net

## 🏗 Architecture
Browser → CloudFront → Private S3 Bucket

## 🔐 Security Features
- S3 bucket is private (Block Public Access ON)
- CloudFront Origin Access Control (OAC)
- Bucket policy restricted to CloudFront only
- AWS WAF enabled
- Default root object configured

## 🛠 Technologies Used
- Amazon S3
- Amazon CloudFront
- AWS WAF
- IAM Policies
- HTML / CSS

## 📸 Features
- Static website with multiple images
- CSS styling
- Secure content delivery via CDN
- DDoS protection via CloudFront

## 🎯 What I Learned
- Configuring private S3 buckets
- Setting up CloudFront distribution
- Using OAC for secure access
- Fixing 403 AccessDenied issues
- Performing CloudFront cache invalidation
