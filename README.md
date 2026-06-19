# cloud-resume-frontend

## 1. Project Overview
A serverless, globally available static website hosting my professional resume. Designed to demonstrate cloud-native deployment practices and automated CI/CD workflows.

## 2. Architecture
- **Platform:** Azure Static Web Apps
- **Deployment:** GitHub Actions (CI/CD Pipeline)
- **Design:** Mobile-responsive HTML5/CSS

## 3. Design Rationale
- **Why Static Web Apps?**
  I chose Azure Static Web Apps to eliminate the need for server management. It provides a global Content Delivery Network (CDN) out    of the box, ensuring fast load times.
  
- **Automation:**
  Integrated GitHub Actions to enable Continuous Integration/Continuous Deployment (CI/CD). This ensures that any update I make to my   code goes live within seconds, without manual intervention.

## 4. Challenges & Troubleshooting
- **Challenge:** Initial DNS propagation delays.
- **Resolution:** Utilized Azure’s built-in managed SSL/TLS certificates and verified the deployment status via the GitHub Actions logs.

## 5. Live Demo
Check out my live resume here: [INSERT YOUR AZURE URL]
