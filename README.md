# role-ros-master [![Build Status](https://travis-ci.org/frankjoshua/ansible-role-ros-master.svg?branch=master)](https://travis-ci.org/frankjoshua/ansible-role-ros-master)<br>

Deploys a ROS master in a Docker container.

## Requirements

See [requirements.yml](requirements.yml)

## Role Variables

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.
ros_ip: "{{ ansible_ssh_host }}"
ros_master_uri: "http://{{ ansible_ssh_host }}:11311"
cpu_arch: "latest"

## Dependencies

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

## Testing

`molecule test`

## License

BSD

## Author Information

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
