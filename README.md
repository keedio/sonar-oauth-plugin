Sonar OAuth Plugin
=====================

In order to use the plugin, you need to add the following properties to your conf/sonar.properties:

sonar.security.realm=oauth

sonar.oauth.providerId=google

sonar.google.clientId.secured=put_your_google_client_id_here
sonar.google.clientSecret.secured=put_your_google_client_secret_here

# optional: if you're using google apps, you can specify a domain name here to restrict access to only those users belonging to that domain
sonar.google.hostedDomain=mydomain.com

sonar.authenticator.createUsers=true
sonar.oauth.sonarServerUrl=your_sonar_url

Configuration for the github provider is similar, use 'github' as the providerId