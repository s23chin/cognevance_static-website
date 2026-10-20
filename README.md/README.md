# Cognevance Project 1: Cloud-Based Static Website Deployment

## Overview

GlobalBridge is a responsive demo website developed using HTML, CSS, and JavaScript. This project demonstrates static website development, version control using Git and GitHub, cloud hosting using AWS S3, and website availability monitoring using UptimeRobot.

The website is deployed on Amazon S3 Static Website Hosting and can be accessed through its public website endpoint.

## Live Website

**Website URL:** http://cognevance-static-website-s23chin.s3-website.eu-north-1.amazonaws.com

**Hosting Platform:** Amazon Web Services (AWS) S3

**AWS Region:** Europe (Stockholm) — `eu-north-1`

**Monitoring Tool:** UptimeRobot

**Monitoring Status:** UP (verified during testing)

## Technologies Used

* HTML5
* CSS3
* JavaScript
* Git and GitHub
* Amazon S3 Static Website Hosting
* UptimeRobot Website Monitoring

## Project Structure

```text
cognevance_static-website/
├── index.html
├── style.css
├── script.js
├── screenshots/
├── docs/
└── README.md
```

## Features

* Responsive website layout for desktop and mobile devices
* Frontend development using HTML, CSS, and JavaScript
* Cloud-based static website hosting
* Public access through an AWS S3 website endpoint
* Website availability monitoring using UptimeRobot

## Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/s23chin/cognevance_static-website.git
   ```

2. Open the project folder:

   ```bash
   cd cognevance_static-website
   ```

3. Open `index.html` in your browser, or use the Live Server extension in Visual Studio Code.

## AWS S3 Deployment

The website was deployed using Amazon S3 Static Website Hosting.

Deployment steps:

1. Create an S3 bucket with a globally unique name.
2. Upload the website files, including `index.html`, `style.css`, and `script.js`.
3. Enable Static Website Hosting in the bucket properties.
4. Set `index.html` as the index document.
5. Configure the required public access settings and bucket policy for public website content.
6. Open the S3 website endpoint and verify that the website loads correctly.

## Website Monitoring

UptimeRobot is used to monitor the availability of the deployed website.

* **Monitor type:** HTTP(s)
* **Monitored endpoint:** AWS S3 website URL listed above
* **Last verified status:** UP

The monitor checks whether the configured website endpoint responds. Monitoring status may change if the website becomes unavailable.

## Security Considerations

* Never upload AWS access keys, credentials, or other secrets to GitHub or the public S3 bucket.
* Only publish files intended for public access.
* Do not collect real personal or confidential information through demo forms.
* The S3 static website endpoint supports HTTP, not HTTPS.
* HTTPS can be configured using Amazon CloudFront and an appropriate TLS certificate. Review AWS pricing before creating additional resources.

## Documentation and Evidence

The following evidence should be maintained as part of the project:

* `screenshots/`: Website screenshots, AWS S3 hosting configuration, and UptimeRobot monitoring status.
* `docs/`: Deployment notes, testing results, and monitoring documentation.

## Project Status

* [x] Responsive website developed
* [x] Website deployed on AWS S3
* [x] Static Website Hosting configured
* [x] Website tested on desktop and mobile
* [x] UptimeRobot monitoring configured and status verified as UP
* [ ] Screenshots and documentation organized in the repository
* [ ] Custom domain and HTTPS configuration, if required

## Author

Developed as part of the Cognevance Technologies Cloud Computing and DevOps Internship project.
