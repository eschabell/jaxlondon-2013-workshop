Hosting JAX London 2013 workshop on Awestruct in OpenShift
==========================================================

This will give you an empty ruby instance on OpenShift for hosting the workshop on an Awestruct site.

Installation
------------

Create OpenShift application

    rhc app create -a jaxlondon2013 -t ruby-1.9 --from-code=https://github.com/eschabell/jaxlondon-2013-workshop.git

You can find the workshop here:

    http://jaxlondon2013-$namespace.rhcloud.com

What is this project doing?
---------------------------

* Install awestruct if not available (ruby gems)
* Update awestruct when already available (ruby gems)
* Install or updage needed deps (ruby gems)
* Generate the site and deploy it

Releases
--------

- none yet.
