# Deployment (TBD)

A deployment will be done to a specific environment only if a changes in the wp-content folder occurred or the root composer file.

To understand more about the WPEngine deployment setup, please refer to the [GitHub Action for WP Engine Site Deployments](https://wpengine.com/support/github-action-deploy/) documentation.

## Development

Development uses the [wpengine-deploy-development.yml](../../.github/workflows/wpengine-deploy-development.yml) deployment file.

In order to deploy you can either:

- push changes to the `development` branch.
- merge a PR to the `development` branch.
- run the "Deploy to the WP Engine Development environment" on GitHub action.

Once deployed, the changes will be available at TBD.

## Staging

Staging uses the [wpengine-deploy-staging.yml](../../.github/workflows/wpengine-deploy-staging.yml) deployment file.

In order to deploy you can either:

- push changes to the `staging` branch.
- merge a PR to the `staging` branch.
- run the "Deploy to the WP Engine Staging environment" on GitHub action.

Once deployed, the changes will be available at TBD.

## Production

Production uses the [wpengine-deploy-production.yml](../../.github/workflows/wpengine-deploy-production.yml) deployment file.

In order to deploy you can either:

- push changes to the `master` branch.
- merge a PR to the `master` branch.
- run the "Deploy to the WP Engine Production environment" on GitHub action.

Once deployed, the changes will be available at TBD.
