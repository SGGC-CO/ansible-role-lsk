# ansible-role-lsk

Prepare SSH key and remove the old host.

## Requirements

none

## Variables

1. playbook.yml

```yaml
pub_rsa_file_path: "path to rsa file of local machine to be added to the server"
```

2. inventory.ini

```yaml
raw_server: "ip address of server"
```

## Dependencies

none

## Example Playbook

`cd tests` and run the playbook with the following command:

```yaml
ansible-galaxy install -r requirements.yml
ansible-playbook -i inventory.ini test.yml
```

## License

BSD

## Author Information

telegram: [@Qteam1](https://t.me/Qteam1)
