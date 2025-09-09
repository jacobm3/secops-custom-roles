# SecOps Custom Roles - gcloud + YAML definitions

## Setup

Cloud shell example:

```
# set your active project ID
gcloud config set project secops-123456

# enable the IAM API
gcloud iam roles create secopsCustomAdmin \
  --project=secops-123456 \
  --file=secops-admin.yaml
```

