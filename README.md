Update: June 2018 moved to [Gitlab](https://gitlab.com/eschabell/jaxlondon-2013-workshop)


Hosting JAX London 2013 workshop on Awestruct in OpenShift
==========================================================
This will give you an empty ruby instance on OpenShift for hosting the workshop on an Awestruct site.


Install with one click
----------------------
[![Click to install OpenShift](http://launch-shifter.rhcloud.com/launch/light/Click to install.svg)](https://openshift.redhat.com/app/console/application_type/custom?&cartridges[]=ruby-1.9&initial_git_url=https://github.com/eschabell/jaxlondon-2013-workshop.git&name=jaxlondon2013)

You can find the workshop here:

    http://jaxlondon2013-$namespace.rhcloud.com


Manual install on OpenShift
---------------------------
Create OpenShift application

    rhc app create -t ruby-1.9 --from-code=https://github.com/eschabell/jaxlondon-2013-workshop.git jaxlondon2013


What is this project doing?
---------------------------

* Install awestruct if not available (ruby gems)
* Update awestruct when already available (ruby gems)
* Install or updage needed deps (ruby gems)
* Generate the site and deploy it

Releases
--------

- v1.1 - added one click install button.

- v1.0 - workshop as given in London, 28 Oct 2013.
