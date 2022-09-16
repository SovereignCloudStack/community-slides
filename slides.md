## Sovereign <!-- .element: style="color:#50c3a5" -->
## Cloud Stack <!-- .element: style="color:#0f5fe1" -->

### Collaboration over Competition <!-- .element: style="color:#50c3a5" -->

Felix Kronlage-Dammers

\<fkr@osb-alliance.com\> <!-- .element: style="color:#50c3a5" -->

Note: special note for myself

<!-- .slide: data-background-image="images/background.jpg" -->


##

![ecos](images/ecos.jpg) <!-- .element height="50%" width="70%" -->


##

```
$ finger fkr

Login: fkr                    Name: Felix Kronlage-Dammers
Job: PO IaaS & Ops @ SCS      Where: OSB Alliance e.V.
E-Mail: fkr@osb-alliance.com  Twitter: @felixkronlage
```


## Die Vision


## 

Sovereign Cloud Stack (SCS) ist eine offene, föderierbare und modulare Cloud- und Containerplattform auf Basis von Open-Source-Software.


## Die Aufgabe


Nur Open-Source garantiert digitale Souveränität durch Interoperabilität, Transparenz und Unabhängigkeit von Ansprüchen Dritter und damit von wirtschaftlicher oder politischer Einflussnahme.


## 

Digitale Souveränität


#### SCS - mehr als nur Datensouveränität 

![Digisov 1](images/digisov-1.png)


#### SCS - mehr als nur Datensouveränität 

![Digisov 2](images/digisov-2.png)


## Die Ziele

* Standardisierung <!-- .element: class="fragment" -->
* Zertifizierbarkeit <!-- .element: class="fragment" -->
* Transparenz <!-- .element: class="fragment" -->
* Nachhaltigkeit <!-- .element: class="fragment" -->
* Föderierung <!-- .element: class="fragment" -->


#

![three pillars](images/three-pillars.png) <!-- .element: class="r-frame" -->


## Wer?


## 

![OSB Alliance](images/logos/osba-logo-claim.svg)

![BMWK](images/logos/bmwk-logo.png) <!-- .element: class="fragment".element height="50%" width="30%" -->


# GAIA-X und SCS?


# 

![scs vs gaia-x](images/scs-vs-gaiax.png)


# 

![scs vs gaia-x](images/scs-vs-gaiax-outline-scs.png)


#

![scs and upstream](images/scs-and-upstream.jpg)


#

![scs architekture bottom up](images/scs-architecture-bottom-up.jpg)


#

![scs architektur](images/201001-SCS-4c.png)


#

![scs acatech](images/Ecosys-SCS-Acatech.png)


## 

![betacloud](images/logos/betacloud-logo.png) <!-- .element height="30%" width="30%" --> ![pco](images/logos/pco-logo.svg) <!-- .element height="30%" width="30%" -->

![wavecloud](images/logos/wavestack-logo.svg) <!-- .element height="30%" width="30%" -->


#

![scs ecosystem](images/scs-ecosystem.png)


### OpenStack == OpenStack?

``` python
def get_server_external_ipv4(cloud, server):
    """Find an externally routable IP for the server.

    There are 5 different scenarios we have to account for:

    * Cloud has externally routable IP from neutron but neutron APIs don't
      work (only info available is in nova server record) (rackspace)
    * Cloud has externally routable IP from neutron (runabove, ovh)
    * Cloud has externally routable IP from neutron AND supports optional
      private tenant networks (vexxhost, unitedstack)
    * Cloud only has private tenant network provided by neutron and requires
      floating-ip for external routing (dreamhost, hp)
    * Cloud only has private tenant network provided by nova-network and
      requires floating-ip for external routing (auro)
```


### Open Source Business Alliance e.V.

* Bundesverband digitale Souveränität
* Wirtschaftsverband mit mehr als 190 Mitgliedsunternehmen
* Interessensvertretung Open Source auf politischer Ebene
