network
=======


What is does this role do?
--------------------------

This role installs and configures acmetool to obtain certificates
automatically from an ACME CA.

Meta
----

Files Managed:
  * /var/lib/acme/*
  * /etc/cron.d/acmetool

Defaults Provided:
  * None

Variables Required:
  * acmetool.hostmaster_email: Email address for alerts
  * acmetool.sites: dictionary of site definitions
    * site: name of site
    * names: names that are valid URLs for this site

Optional Variables:
  * None

Files Required:
  * None

Optional Files:
  * None

Conflicting Roles:
  * None

Depends On:
  * None
