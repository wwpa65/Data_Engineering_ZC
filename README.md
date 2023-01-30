# Data_Engineering_ZC
DATA ENGINEERING ZOOM CAMP

Week 1:

DOCKER_SQL


TERRAFORM_GCP
Codes: 
# Refresh service-account's auth-token for this session
gcloud auth application-default login

# Initialize state file (.tfstate)
terraform init

# Check changes to new infra plan
terraform plan -var="favorable-tree-346416"
# Create new infra
terraform apply -var="favorable-tree-346416"
