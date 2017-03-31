# Ansible Role: Logstash

This role installs and configures Logstash 5.x for the Elastic stack.

It has only been designed to work on Ubuntu 16.04, but other Debian flavours
should also work.


## Requirements

None.


## Role Variables

TODO


## Resources

Documentation related to Logstash can be found at the links below:

- [documentation](https://www.elastic.co/guide/en/logstash/current/index.html)


## Dependencies

None.


## Example Playbook

```yaml
- hosts: servers
  become: yes

  roles:
    - role: jradtilbrook.logstash
```


## License

MIT
