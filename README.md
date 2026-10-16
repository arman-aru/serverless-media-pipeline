# serverless-media-pipeline

> Event-driven image pipeline on AWS — S3 upload triggers Python Lambda to resize, convert to WebP and generate AI alt text, with SQS and DynamoDB.

![status](https://img.shields.io/badge/status-in%20development-yellow) ![license](https://img.shields.io/badge/license-MIT-green)

## Overview

An event-driven image pipeline on AWS. Uploading an image to S3 triggers a Python Lambda that resizes it, converts it to WebP and generates accessible alt text with AI, then stores the metadata in DynamoDB.

## Features

- Automatic processing on S3 upload
- Responsive sizes and WebP conversion
- AI-generated alt text for accessibility and SEO
- SQS queue with retries and a dead-letter queue
- Image metadata stored in DynamoDB
- Infrastructure as code, logging and alarms

## Tech stack

Python · AWS Lambda · S3 · SQS · DynamoDB · Pillow · Terraform / AWS SAM

## License

[MIT](LICENSE) © Arman Salek
