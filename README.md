# apicurio

 keycloak-7.0.1 % ./bin/standalone.sh
 ./bin/standalone.sh -c standalone-apicurio.xml -Djboss.socket.binding.port-offset=100
 
 https://www.apicur.io/studio/docs/setting-up-a-development-environment
 
 https://github.com/Apicurio/apicurio-studio/issues/1257
 
 If that's the case, you will need to either change that to public or modify the Apicurio Studio configuration (in keycloak.json). 
 I don't have the instructions offhand for what changes you would need to make in keycloak.json - you'd have to look that up in the Keycloak docs.
 
 
