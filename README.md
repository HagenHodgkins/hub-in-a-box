# hub-in-a-box
An Ansible Role for standing up a "starter hub" targeting RHEL / CentOS.

** This is not supported by HUBzero, rather a tanget of me setting up and destroying hubs quickly. **

This takes about 30 minutes to run: downloading packages, provisioning OpenVZ tool container templates, configuring the CMS, etc.

Assumes a blank EC2 instance or DigitalOcean droplet.

Once you provision your host, you could add the `hub-in-a-box` role to install all HUBzero packages.
``` roles:
    - hub-in-a-box```
