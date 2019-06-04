Thoth: external JanusGraph Service
==================================

*OBSOLETED* This role is no longer used by Project Thoth, we have migrated the knowledge graph to Dgraph.

This role will create an OpenShift Service object to integrate an external JanusGraph Server.

Role Variables
--------------

This role requires a target host name that is running the JanusGraph Server and a namespace in which the service should be created.


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - role: thoth-station.external_janusgraph_service
          janusgraph_server_ip_address: 10.10.10.10
          namespace: thoth-test-core

License
-------

GPLv3

Author Information
------------------

The Thoth Station Team.