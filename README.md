c4a
===

C4A reseller scrips and configuration.

These configuration files are the bare minimum to get connected to the c4a platform and
are assuming you have installed the base of Zarafa, Postfix and Openldap and have proper
knowledge of the mentioned software.

You need the information you got after signing the reseller agreement and a working controlpanel
setup with these configuration files.


- zarafa
 server.cfg
 ldap.cfg
 00createstore create store script with language selection
   
- ldap
   slapd.cfg
   needed addition schema files (c4a specific)

- postfix
   main.cf with ssl/tls
   main.cf.no.tls.cf with no ssl/tls

- helper scripts
   various scripts
   
For a basic setup, help with the installation please send an email to :

Development and Operations - <devops@campai.nl>

Reseller Information       - <sales@campai.nl>

