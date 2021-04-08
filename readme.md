# Login to GCP on a local machine:
gcloud auth login --no-launch-browser

And follow instructions in the browser.

# List all projects:
gcloud projects list

# Print current project name:
gcloud config get-value project

# Set current project:
gcloud config set project static-site-demo-308200

#Deploy the main version:
gcloud app deploy

#Deploy the second version:
gcloud app deploy --version someone --no-promote

# Link a custom domains to GCP AppEngine site.
Example: https://me.kanshyn.com/

