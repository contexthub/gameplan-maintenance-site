gameplan-maintenance-site
=========================

## To deploy

1. Make needed changes
2. Commit changes to github
3. middleman build
4. middleman s3_sync

## .s3_sync file

```
---
aws_access_key_id: <AWS Access Key>
aws_secret_access_key: <AWS Secret Access Key>
```

## Site url

   http://gameplan-maintenance-dev.s3.amazonaws.com/index.html
