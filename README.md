# heroku-buildpack-envkey

Heroku buildpack for loading ENVKEY environment variables

Original source: https://github.com/envkey/envkey-heroku-buildpack

## Usage

### Add the buildpack

1. On the settings page for your app, e.g. https://dashboard.heroku.com/apps/MY-APP/settings, find the `Buildpacks` section.
1. Click on the 'Add buildpack' button.
1. Provide the URL for this repository: `https://github.com/LambdaSchool/heroku-buildpack-envkey.git`
1. Click 'Save Changes'
1. Verify that this build pack is used **very first**. Later build packs will surely require the environment variables.
    
### Set the environment variable

While still on the settings page, add an environment variable `ENVKEY=such-secrets` that is defined using the EnvKey app.
