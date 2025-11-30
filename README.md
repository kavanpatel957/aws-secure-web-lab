# aws-secure-web-lab

## 🎯 Goal
Deploy an intentionally misconfigured S3 static website on AWS, identify security issues, fix them, and document the impact.

## 🔥 Threat Model
- Public access to sensitive content
- Lack of logging and monitoring
- Over-permissive IAM policies

## ❌ Initial Misconfigurations
- S3 public bucket
- No encryption
- No bucket policy restrictions
- No CloudTrail logs

## 🛠 Fixes Applied
- Block Public Access enabled
- Encrypted bucket (SSE-S3 or KMS)
- Principle of least privilege IAM
- CloudTrail + S3 access logging enabled

## 📊 Results
- Reduced public exposure from `AllUsers` global access → IAM-restricted
- Logging visibility: 100% S3 actions captured
- Compliance posture improved (CIS AWS Benchmark checks)

## 📂 Proof & Screenshots
(uploding...)

## 🧠 Tools Used
- AWS Console
- IAM Access Analyzer
- Trusted Advisor / AWS Config

## 📅 Timeline
Day 1: Deployment + misconfig
Day 2: Fixes + logs
Day 3: Documentation + short demo video

