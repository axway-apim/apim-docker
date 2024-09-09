# apim-docker
Docker compose script for minimal APIM install. Useful for testing and development.

## Environment Configuration
This example uses a merge folder relative to the compose file.  Refer to the [Deploy API GAteway with Axway docker images](https://docs.axway.com/bundle/axway-open-docs/page/docs/apim_howto_guides/configuring_apigw_container/index.html) for full documentation on how to use the merge folder to managange runtime configuration.
At a minimum, you must place a valid license file in the ./merge/apigateway/conf/licenses folder.

## Setup
Create a directory to mount as a docker volume to persist the configuration information
This example uses ./cassandra which gets mounted to /var/lib/cassandra
