# braidwell.com web site

Static files for the WordPress site hosted on Cloudflare.

&nbsp;

## Summary info

Cloudflare console / Braidwell account
- https://dash.cloudflare.com/2e361b0284bdb4f6d4744fef5e58a5bc

&nbsp;

Deployments can be manually created by
- Zipping the repo contents: `zip -r files.zip .`
- Visiting the Cloudflare Worker page for this project
  - https://dash.cloudflare.com/2e361b0284bdb4f6d4744fef5e58a5bc/pages/view/prod-static-braidwell-com-site
- Choose "Create new deployment" and upload the zip file
- Choose the "Save and Deploy" option.

&nbsp;

We will be switching to a Github automated deploy @@later.
