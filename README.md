# StudioAnjou - Static Website

This was converted to a completely static site from a WordPress site.
It's markup is therefore a bit shite. But it works. And is fast. And never requires upgrading. And is cheap to host. And is un-hackable.

So not as shite as it was.

https://studioanjou.com/

## Deployment
Until I add a github workflow, this is manual...

```bash
aws s3 sync . $STUDIOANJOU_WWW_S3_BUCKET --exclude ".cursor/*" --exclude ".git/*" --exclude ".gitignore" --exclude "README.md" --delete --dryrun
aws cloudfront create-invalidation --distribution-id $STUDIOANJOU_WWW_S3_CF_ID --paths "/*"
```
