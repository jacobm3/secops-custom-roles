# SecOps Custom Roles

## Roles
This repo contains Terraform code for custom SecOps IAM roles, if you require something more granular than the prebuilt Chronicle API Admin, Editor, and Viewer roles.

The latest pre-built GCP role definitions can be found in the console here:

https://console.cloud.google.com/iam-admin/roles/details/roles

https://console.cloud.google.com/iam-admin/roles/details/roles%3Cchronicle.admin

## Setup

Note: you must enable the IAM API in your SecOps project before using Terraform to manage custom roles.

Example in cloud shell:

```
# set your active project ID
gcloud config set project secops-123456

# enable the IAM API
gcloud services enable iam.googleapis.com
```

