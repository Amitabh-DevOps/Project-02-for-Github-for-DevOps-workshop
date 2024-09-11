# Project-02-for-Github-for-DevOps-workshop

## Overview

This project demonstrates the deployment of a static YouTube clone using Amazon Web Services (AWS) S3. The purpose of this project is to showcase how to host a static website on AWS S3 and make it publicly accessible.

You can view the live demo of the static YouTube clone [here](http://youtube-clone12.s3-website-us-east-1.amazonaws.com/).

## Features

- **Static YouTube Clone**: A basic static website mimicking the layout and design of YouTube.
- **Hosted on AWS S3**: The website is deployed and served from an AWS S3 bucket.
- **Public Access**: The website is publicly accessible via a web URL.

## Getting Started

### Prerequisites

- AWS Account
- Basic knowledge of AWS S3
- Familiarity with static website deployment

### Deployment Steps

1. **Create an S3 Bucket**:
   - Go to the AWS Management Console.
   - Navigate to S3 and create a new bucket.
   - Ensure the bucket name is globally unique.

2. **Configure Bucket for Static Website Hosting**:
   - In the S3 bucket properties, enable static website hosting.
   - Set the index document to `index.html`.

3. **Upload Website Files**:
   - Upload your static website files (HTML, CSS, JavaScript) to the S3 bucket.

4. **Set Bucket Policy for Public Access**:
   - Configure the bucket policy to allow public read access to your files.

5. **Access Your Website**:
   - Use the provided S3 website URL to view your deployed static website.

## Project Structure
/project-root ├── index.html ├── styles │ └── style.css └── scripts └── script.js
/project-root ├── .github ├── workflows │ └── main.yml 

## Contributing

Feel free to fork the repository and submit pull requests. If you encounter any issues or have suggestions for improvements, please open an issue on GitHub.

## Acknowledgments

- AWS S3 for providing the platform to host static websites.
- Inspiration from YouTube’s design and functionality.

For detailed information and implementation, you can read this [blog post](https://amitabhdevops.hashnode.dev/github-for-devops).
