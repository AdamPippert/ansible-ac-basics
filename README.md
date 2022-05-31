# ansible-ac-basics

This repo contains some basic examples to use in Ansible Automation Controller, including API access, RBAC, and OpenShift content.

To use, create a "vars.yml" file with the following variables defined (and DO NOT commit this file to a fork or copy of the repo!)

sample vars.yml file:

---

acadminuser: <administrator user for Automation Controller instance>
acadminpass: <administrator password for Automation Controller instance>
controller: <URL for Automation Controller instance>

clusterurl: <base URL for OpenShift cluster instance>
ocadminuser: <administrator user for OpenShift cluster instance>
ocadminpass: <administrator password for Openshift cluster instance>
