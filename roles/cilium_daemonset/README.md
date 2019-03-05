# Cilium

Deploy Cilium daemonset, which registers as the CNI plugin.  

## Requirements

* Ansible 2.2

## Installation

To install, set the following inventory configuration parameters:

* `openshift_use_cilium=True`
* `openshift_use_openshift_sdn=False`
* `os_sdn_network_plugin_name='cni'`

### Contact Information

Author: XXXX

Check out the `#kubernetes` channel on [cilium slack](https://cilium.io/slack) if you have questions.
