# Nested Project Outline

I will be migrating my friend's business website to AWS and incorporating some new features.

Current website:

<https://magsolutions-usa.com/>

## Infrastructure

As of now, the website is in a static state.  The easiest and most cost effective
way to migrate would be to make use of S3 to host the website.  I'm pretty sure
that the original website was built using google pages.  I need to figure out
how to get the source code so that I can upload it to the bucket.  I plan to
use Terraform to create all the resources, so that in the future we can deploy
to his own account.  
