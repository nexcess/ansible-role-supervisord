# Ansible Role: Supervisord

Installs & configures Supervisord.

## Role Variables

See `defaults/main.yml`.

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
