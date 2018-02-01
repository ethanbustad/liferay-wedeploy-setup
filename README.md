# Purpose

To make deployment of a Liferay instance on WeDeploy easy for demo projects.

# Usage

Requires WeDeploy CLI. Install with

    curl https://cdn.wedeploy.com/cli/latest/wedeploy.sh -sL | bash

To deploy all services to a project, run the following command from the repo's base directory

    we deploy [--project $project_name]

To deploy just a single service, change directory to the service you want to deploy, and run the above command. Deployment seems to be somewhat fickle and will often require multiple attempts, so usually deploying one service at a time is a quicker route to successfully deploying the whole project.

For more information on how to use the CLI, see https://wedeploy.com/docs/intro/using-the-command-line/.
