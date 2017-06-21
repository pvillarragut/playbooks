# playbooks
A set o useful ansible playbooks

- **system**: Manage base system packages and install NTP service
- **bash_aliases**: Add bash aliases to user . Needs a list of dictionaries `bash_aliases` with a  `alias` and `commmand` values.
- **rundeck**: Install rundeck server an client
- **ansible**: Install ansible client 
- **awscli**: Install AWSCli and boto library. Need hosts variables `aws_access_key_id` , `aws_secret_access_key` and `aws_region`
- **docker**: Enable docker Subsystem. Install docker-compose system and configure rsyslog to manage docker logs
- **docker_compose** - Configure and manage docker_compose files. Need list variables `docker_containers` and `docker_config_files` (view examples in role/defaults folder)
