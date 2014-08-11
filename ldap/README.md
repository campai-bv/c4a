c4a
===

C4A reseller scrips and configuration


Openldap basic configuration.
The config is "plain" openldap, if you wish you can convert this to OLC style setup.

Be sure to load the extra 4 schema's also.

- slapd.conf (main openldap config)
Please edit this, and fill in the values mentioned below "#READ ME!".
Also fill in the credentials and baseDN you have gotten from us to setup a succesfull slave.

- schema (The needed extra schema's, without these your setup will not work)
campai.schema (c4a / controlpanel specific objects)
zarafa.schema (zarafa specific objects)
qmail.schema  (zarafa specific objects)
amavis.schema (only needed if you implement the amavis avas scanner)