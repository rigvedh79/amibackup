# Deployment Guide

## Project

Static Website Hosting on Amazon S3

## Prerequisites

- AWS account
- Amazon S3 access
- Static website files
- Basic knowledge of AWS IAM and S3 permissions

## Deployment Steps

### 1. Create an S3 Bucket

1. Sign in to the AWS Management Console.
2. Open Amazon S3.
3. Select **Create bucket**.
4. Enter a globally unique bucket name.
5. Choose an AWS Region.
6. Create the bucket.

### 2. Upload Website Files

Upload the following files:

- `index.html`
- `error.html`

### 3. Enable Static Website Hosting

1. Open the bucket.
2. Select the **Properties** tab.
3. Locate **Static website hosting**.
4. Select **Enable**.
5. Choose **Host a static website**.
6. Enter:

```text
Index document: index.html
Error document: error.html
