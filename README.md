Install RedHat OpenShift Origin in your development box.


* Installation

1. Create a VM as explained in [[http://www.youtube.com/watch?v=-OOnGK-XeVY][this video]] by Grant Shipley

2. Define the domain name, user name and password defined at installation time of Centos7.

#+BEGIN_EXAMPLE
# export DOMAIN=org.sistcoop.org
# export USERNAME=carlos
# export PASSWORD=password
#+END_EXAMPLE

3. Run the automagic installation script as root:

#+BEGIN_EXAMPLE
# curl https://raw.githubusercontent.com/carlosthe19916/installcentos/master/install-openshift.sh | /bin/bash
#+END_EXAMPLE
