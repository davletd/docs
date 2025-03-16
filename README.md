# Cloudgeni AI Agent Documentation

This repository contains the documentation for Cloudgeni AI Agent, a powerful tool designed to help you manage and monitor your infrastructure, identify issues, and ensure compliance with best practices.

## Documentation Structure

The documentation includes:

- **Introduction**: A brief overview of Cloudgeni AI Agent and its key features
- **Cloudgeni AI Agent Guide**: A comprehensive guide to setting up and using Cloudgeni AI Agent
  - Step-by-step setup instructions
  - Detailed explanations of key features
  - Best practices and troubleshooting tips

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command:

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where docs.json is):

```
mintlify dev
```

## Image Assets

The documentation references images that should be placed in the `/images/cloudgeni/` directory:

1. `cloudgeni-dashboard.png` - Screenshot of the main Cloudgeni dashboard
2. `select-repository.png` - Screenshot of the repository selection screen
3. `install-authorize.png` - Screenshot of the installation and authorization screen
4. `infrastructure-issues.png` - Screenshot of the infrastructure issues page
5. `cloud-compliance.png` - Screenshot of the cloud compliance section
6. `cost-optimization.png` - Screenshot of the cost optimization section
7. `repository-selection.png` - Screenshot of the repository selection process

Please refer to `extract-cloudgeni-images.md` for detailed instructions on extracting and saving these images.

## Publishing Changes

Install the Github App to auto propagate changes from your repo to your deployment. Changes will be deployed to production automatically after pushing to the default branch.

## Troubleshooting

- If Mintlify dev isn't running, run `mintlify install` to re-install dependencies.
- If a page loads as a 404, make sure you are running in a folder with `docs.json`.
