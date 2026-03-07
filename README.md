# StudioAnjou - Static Website
Angela's website...

https://studioanjou.com/

## Deployment
Until I add a github workflow, this is manual...

```bash
aws s3 sync . $STUDIOANJOU_WWW_S3_BUCKET --exclude ".cursor/*" --exclude ".git/*" --exclude ".gitignore" --exclude "README.md" --delete --dryrun
aws cloudfront create-invalidation --distribution-id $STUDIOANJOU_WWW_S3_CF_ID --paths "/*"
```
