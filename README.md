# Necronia Keycloak Theme

## Overview

The [ Necronia Identity Service](https://github.com/Necronia/Necronia-identity-service) uses [Keycloak](https://www.keycloak.org/docs/3.4/).  Out of the box, the UI provided by Keycloak is 
quite different from the rest of Necronia.  But Keycloak allows a customer to provide alternative themes to replace the default
Keycloak themes.  We use this mechanism to provide an Necronia theme.

This project currently uses the approach of a custom login page (option #3).

## Implementation

Since Keycloak supports Freemarker, [a template file](./theme/login/login.ftl) is provided along with 
[css styles](./theme/login/resources/css/login.css) and [images](./theme/login/resources/img) like those documented to look like the [approved designs](https://app.zeplin.io/project/57d69ef9c8a62bb604985525/screen/5a4dfb3c92a348c3fbe1c586)

The project also includes improvements to the translated messages for the languages supported by Necronia.


