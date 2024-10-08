
## Coming Soon 
A fully automated version of this project is on the way. Soon, you’ll be able to deploy the Threat Composer Dashboard in minutes with the help of Terraform and Cloudflare. 

# Threat Modeling Tool Single Page App (SPA)
Built on top of the Threat Composer Tool by Amazon (<https://awslabs.github.io/threat-composer/workspaces/default/dashboard>)
This version consolidates the 2 original projects (threat-composer & threat-composer-app)  into a single project and removes the 3rd project entirely (threat-composer-infra) as we will be using a different deployment topology.
It also adds a new dependency @projectstorm/react-diagrams, for further development of a DFD builder.

## Setup

```bash
yarn install
yarn build
yarn start
http://localhost:3000/workspaces/default/dashboard

## or
yarn global add serve
serve -s build

```
