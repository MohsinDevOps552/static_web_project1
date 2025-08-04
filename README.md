 Static Website Deployment on AWS Using Terraform

This project sets up a static website hosted on an AWS S3 bucket using Terraform. It includes configuration for S3 website hosting, uploading static files, and optionally setting up CloudFront and Route 53 for CDN and custom domain.

---

 Project Structure
terraform-s3-static-site/
│
├── provider.tf  # AWS provider configuration
├── s3.tf        # S3 bucket and policies
├── variables.tf # Input variables
├── outputs.tf   # Outputs like bucket URL
└── website/     # Your website files (index.html, style.css, etc.)

🔧 Prerequisites

- Terraform CLI v1.0+
- AWS CLI configured
- Git installed


⚙️ How to Use

 1. Clone the repo

bash
git clone https://github.com/your-username/terraform-s3-static-site.git
cd terraform-s3-static-sit




2. Initialize Terraform

terraform init

3. Plan the deployment


terraform plan


4. Apply the changes

terraform apply


5. Visit Your Website
After successful apply, Terraform will output a URL like:

Edit
http://your-bucket-name.s3-website-us-east-1.amazonaws.com


Screenshots

Static-web\screenshot
