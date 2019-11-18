Automatic L3vpn Multivendor with Ansible and NAPALM (IOS,XR,Junos,etc)

Automatically create and deploy an L3VPN service (template creation, configuration and validation that the network is in the way its configuration was planned and that there are no floating configurations), the l3vpn service model is loaded into an ansible playbook and based on The same model creates a template of configurations for each type of equipment involved in the service and then through NAPALM-Ansible library deploys the service to multiple network devices, in the example shown in the demonstration video on YouTube (I leave link below) an automated deployment of l3vpn to devices with IOS, XR, JunOS is shown and it is validated that they announce prefixes, BGP is used as PE-CE protocol, but any type of IGP can be used in the same way as PE-CE.

Technology stack
Python 3.x, Ansible 2.7 or higher, it can be run on windows as long as ubuntu as WSL is installed and from there run it

Status:
Only one version already tested and validated in emulated enviroment (EVE-NG with multivendor ISP Topology, see the video link below)

