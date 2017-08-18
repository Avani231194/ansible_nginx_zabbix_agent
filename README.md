## Ansible Role for Hosting a Virtual Website using NGINX and setting a zabbix agent and adding that agent to zabbix server using auto registration


1. This role is creating a virtual website that can accessed by hitting the IP of the server on the browser.
2. creating a user
3. Setting up Zabbix agent on the server, adding it to zabbix server using auto registration

------------------------------------------------------------------------------

> For Role:

 Edit your "site.yml" accordingly

    ---
    - hosts: NAME_OF_YOUR_HOST_GROUP_DEFINED_IN_HOSTS_FILE
       roles:
          - { role: PATH_TO_YOUR_ROLE }

Also, Add your hosts into the host file under a group that will be defined inside site.yml


#Henceforth, you can run run the playbook by :

   ansible-playbook site.yml

or ansible-playbook path_to_site.yml
 
> Assuming that the zabbix-server has already been setup, and actions has been preconfigured.

##NOTE: Change the IP of your Zabbix Server accordingly






 

