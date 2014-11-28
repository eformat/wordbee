The OpenShift `jbossews` cartridge documentation can be found at:

http://openshift.github.io/documentation/oo_cartridge_guide.html#tomcat


To Install this Openshift application:

rhc app create wordbee jbossews-2.0 -s --from-code https://github.com/eformat/wordbee.git --timeout 3600
