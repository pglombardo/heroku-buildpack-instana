# Heroku buildpack for Instana agent

The following environment variables must be set on the Heroku app:

 * INSTANA_AGENT_KEY
 * INSTANA_LOCATION
 * INSTANA_USERNAME
 * INSTANA_PASSWORD
 * INSTANA_TENANT
 * INSTANA_TENANT_UNIT

Then do `heroku buildpacks:add https://github.com/kek/heroku-buildpack-instana.git`
