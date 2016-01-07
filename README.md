# Staticfile Test Applications

A collection of applications used for testing the staticfile buildpack

## Applications

| Name | Description
| ---- | -----------
| `normal-staticfile` | Cloned from `normal_staticfile` cloudfoundry-community/staticfile-buildpack-acceptance-tests
| `alternate-root` | Cloned from `alternate_root` cloudfoundry-community/staticfile-buildpack-acceptance-tests

### Output Content

All applications support the following REST operations:

| URI | Description
| --- | -----------
| `GET /` | The health of the application

## Deploying to Cloud Foundry

Each test application contains a `manifest.yml` file which allows the built application to be deployed to Cloud Foundry by simply issuing:

```
cf push
```
