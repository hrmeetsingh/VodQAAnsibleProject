# VodQAAnsibleProject
Demo Ansible projects for ThoughtWorks' VodQA event. 

The subfolders contain demo Ansible projects and some supporting code. 

## ansible_roles
  Demonstration of installing Apache2 role on two Ubuntu 16.04 hosts using Ansible Playbook.
  
  __Prerequisites__ -
  * Docker container with Ubuntu 16.04 as base image, OpenSSH service running and port 22 mapped to one of the port on host (updated in the hosts file)
  * Virtualbox running an Ubuntu 16.04 image with OpenSSH running
  * Both docker container and virtualbox VM have SSH keys setup with machine running ansible.
