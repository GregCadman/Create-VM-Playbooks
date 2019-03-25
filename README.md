# Create-VMs-Playbook
These playbooks create new virtual machines in Vcenter and help in provisioning

Create_VMs playbook create new virtual machines in vcenter. It pulls variables both from user input and from a seperate text file (which I've included a sample of).

Winbind_join playbook joins the servers to an AD domain by using winbind. It copies a lot of 'master' files over from the machine running ansible.

SSSD_join playbook joins the servers to an AD domain by using SSSD. Similar to the winbind playbook but I included both methods in case anyone is picky. They do the same thing so there is no point in running both. 
