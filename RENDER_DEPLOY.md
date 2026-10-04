# Render deployment

This package is prepared as a Render Static Site. The original PHP homepage/blog files were converted to static HTML because Render Static Sites do not execute PHP.

## Render settings
- Service type: Static Site
- Build Command: leave blank
- Publish Directory: `.`
- Recommended repo branch: `main`

The included `render.yaml` can also configure the service when using Render Blueprints.

## Important
Do not delete the Hostinger site until the Render deployment and custom-domain DNS are tested.

The supplied archive contained `blog/index.php` and `blog/posts/post-1.php`; there was no `post-2.php`, so the missing second blog card was not carried over as a broken link.
