Role Name
=========

Install and configure a set of quagga based BGP routers on RHEL variant systems

Requirements
------------

- Currently only written to work on RHEL variants
- Dependent on having access to quagga package for installation

Role Variables
--------------

TBD...

Dependencies
------------

None

Example Inventory
-----------------

    [bgp_routers]
    bgp-1.example.com
    bgp-2.example.com

Example Playbook
----------------

    - name: playbook to create RHEL 7 based quagga BGP routers
      hosts: bgp_routers
      become: true
      vars:
      roles:
        - role: ansible-quagga-bgp

License
-------

GNUv3

Author Information
------------------

Kevin Jones. Principal Cloud Domain Architect. Red Hat
