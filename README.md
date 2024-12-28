## Roman-Numerals-Converter-Application

Full-stack web application demonstrating cloud deployment automation using AWS CloudFormation, Python Flask, and Infrastructure as Code practices.

## Project Highlights

✨ Infrastructure as Code with AWS CloudFormation  
✨ Full-stack development with Python Flask  
✨ Automated cloud deployment  
✨ CI/CD implementation with AWS CLI  
✨ Infrastructure automation with user data scripts


## Key Features

• Cloud Infrastructure
  - Automated EC2 deployment
  - Security group configuration
  - Parameter store integration
  - Dynamic resource provisioning

• Application
  - RESTful web service
  - Input validation
  - Error handling
  - Responsive web interface

• DevOps Practices
  - Infrastructure as Code
  - Automated deployment
  - CLI automation
  - Version control integration

## Quick Start

1. **Prerequisites**
   - AWS Account
   - AWS CLI configured
   - Python 3.x
   - Git

2. **CloudFormation Deployment**
   ```bash
   # Deploy using AWS CloudFormation
   aws cloudformation create-stack \
     --stack-name roman-converter \
     --template-body file://template.yml \
     --parameters ParameterKey=KeyPairName,ParameterValue=your-key
   ```

3. **CLI Deployment**
   ```bash
   # Deploy using AWS CLI
   ./cli.sh deploy
   ```

4. **Access Application**
   - Web interface available at the URL in CloudFormation outputs
   - Supports numbers between 1-3999
   - Returns Roman numeral conversion


## Project Structure
```
.
├── template.yml          # CloudFormation template
├── cli.sh               # AWS CLI deployment script
├── app/
│   ├── app.py           # Flask application
│   └── templates/       # HTML templates
└── scripts/             # Deployment scripts
```
