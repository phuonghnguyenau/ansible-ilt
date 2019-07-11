Advanced Deployment with Red Hat Ansible Automation ILT
=======================================================
Lab exercises implemented by Phuong. Was forked from https://github.com/tonykay/bad-ansible.

Playbooks
---------
* cleanup.yml - Deletes applications on the nodes
* osp_cleanup.yml - Deletes OpenStack instances
* osp_image.yml - Upload RHEL guest image to OpenStack
* osp_instances.yml - Create OpenStack instances
* osp_three_tier_app.yml - Deploys the Three Tier applications
* smoke_test.yml - Verifies if the Three Tier applications have been set up correctly
