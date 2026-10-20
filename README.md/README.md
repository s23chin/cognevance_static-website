# Cognevance Project 1: Cloud-Based Static Website Deployment

## 1. Project Overview

GlobalBridge is a responsive demo website developed using HTML, CSS, and JavaScript. This project demonstrates static website development, version control using Git and GitHub, cloud deployment using Amazon S3, and website availability monitoring using UptimeRobot.

The website is hosted using AWS S3 Static Website Hosting and has been tested on desktop and mobile devices.

## 2. Live Deployment

- **Live Website:** [GlobalBridge Website](http://cognevance-static-website-s23chin.s3-website.eu-north-1.amazonaws.com)
- **GitHub Repository:** [cognevance_static-website](https://github.com/s23chin/cognevance_static-website)
- **Cloud Provider:** Amazon Web Services (AWS)
- **Hosting Service:** Amazon S3 Static Website Hosting
- **AWS Region:** Europe (Stockholm) — `eu-north-1`
- **Website Monitoring:** UptimeRobot
- **Last Verified Monitoring Status:** UP

## 3. Technologies Used

- HTML5
- CSS3
- JavaScript
- Git and GitHub
- Amazon S3
- UptimeRobot

## 4. Project Structure

```text
cognevance_static-website/
├── index.html
├── style.css
├── script.js
├── screenshots/
├── docs/
└── README.md
```

## 5. Features

- Responsive layout for desktop and mobile devices
- Frontend developed using HTML, CSS, and JavaScript
- Static website hosting on AWS S3
- Public website access through an S3 website endpoint
- Website availability monitoring using UptimeRobot
- Version control and source code management using Git and GitHub

## 6. Run the Project Locally

### Prerequisites

- A web browser
- Git
- Visual Studio Code (optional)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/s23chin/cognevance_static-website.git
   ```

2. Navigate to the project directory:

   ```bash
   cd cognevance_static-website
   ```

3. Open `index.html` in a web browser, or use the Live Server extension in Visual Studio Code.

## 7. AWS S3 Deployment

The website was deployed using Amazon S3 Static Website Hosting.

### Deployment Steps

1. Create an S3 bucket with a globally unique name.
2. Upload the website files, including `index.html`, `style.css`, and `script.js`.
3. Enable Static Website Hosting in the bucket properties.
4. Configure `index.html` as the index document.
5. Configure the required public access settings and bucket policy for the intended public website files.
6. Open the S3 website endpoint and verify that the website loads correctly.

## 8. Website Monitoring

UptimeRobot is used to monitor the availability of the deployed website.

- **Monitoring Tool:** UptimeRobot
- **Monitor Type:** HTTP(s)
- **Monitored URL:** [GlobalBridge Website](http://cognevance-static-website-s23chin.s3-website.eu-north-1.amazonaws.com)
- **Observed Status:** UP

The monitor checks the configured endpoint and reports whether it receives the expected response. An UP status confirms a successful monitoring check, but it does not guarantee that every website feature is functioning correctly.

## 9. Security Considerations

- Never commit AWS access keys, passwords, or other secrets to GitHub.
- Only upload files intended for public access to the public website bucket.
- Do not collect real personal or confidential information through demo forms.
- The Amazon S3 static website endpoint supports HTTP and does not provide HTTPS directly.
- HTTPS can be configured using Amazon CloudFront and an appropriate TLS certificate. Review AWS pricing before creating additional resources.

## 10. Documentation and Evidence

The repository includes folders for project evidence and documentation.

- **`screenshots/`** — Screenshots of the deployed website, AWS S3 configuration, and UptimeRobot monitoring.
- **`docs/`** — Deployment notes, testing results, and monitoring documentation.

## 11. Project Status

- [x] Responsive website developed
- [x] Website deployed on AWS S3
- [x] Static Website Hosting configured
- [x] Website tested on desktop and mobile
- [x] UptimeRobot monitoring configured and verified as UP
- [x] Screenshots uploaded to the GitHub repository
- [ ] Monitoring report saved in `docs/monitoring.md`
- [ ] Custom domain and HTTPS configured, if required by the project requirements

## 12. Author

Developed as part of the **Cognevance Technologies Cloud Computing and DevOps Internship**.

