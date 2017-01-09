# Ansible Role: Supervisord

Installs & configures Supervisord.

## Role Variables

See `defaults/main.yml`, specifically the supervisord_programs variable which controls all program variables.

## Dependencies

- nexcess.repo-epel (or nexcess.server)

## Add to Requirements

    - src: https://github.com/nexcess/ansible-role-supervisord.git
      name: nexcess.supervisord

## Example Playbook

    - hosts: server
      roles:
        - nexcess.supervisord

## License

MIT / BSD
