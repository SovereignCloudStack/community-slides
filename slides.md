## Sovereign Cloud Stack

### Overview - GAIA-X Hackathon \#5

Eduard Itrich \<itrich@osb-alliance.com\> <!-- .element: style="color:black" -->

Felix Kronlage-Dammers \<fkr@osb-alliance.com\> <!-- .element: style="color:black" -->

Note:

<!-- .slide: data-background-image="images/background.jpg" -->


##

![Ecosys - Acatec](images/Ecosys-SCS-Acatech.png)

Note:


##

![SCS Architecture Bottom Up](images/scs-architecture-bottom-up.jpg)

Note:


##

![SCS Architecture Layers](images/201001-SCS-4c.png)

Note:


##

![Cross Cluster Networking](images/cross-provider-cluster-networking.png)

Note:


##

![Jeystone to KeyCloak to KeyCloak to external IdP](images/keystone-to-keycloak-to-keycloak-to-external-idp.png)

Note:

* Customers get an OpenStack domain (with one or several OpenStack projects and none to several k8s clusters)
  * User Management is per domain
  * Keystone can gets identities from local keycloak (via Open ID Connect Federation), customer owns a realm
  * Keycloak can be set up to accept identities from other keycloaks or other trusted IdPs (OIDC/SAML)


## 

![Keycloak - Keystone](images/Keycloak-Keystone-diagram.png) 

Note:


## 

![OpenStack v3oidcpassword sequence](images/openstack-v3oidcpassword.drawio.png)

Note:
