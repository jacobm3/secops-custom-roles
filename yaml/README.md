# SecOps Custom Roles - gcloud + YAML definitions

## Setup

Cloud shell example:

```
# enable the IAM API
gcloud iam roles create secopsCustomAdmin \
  --project=secops-123456 \
  --file=secops-admin.yaml
```

