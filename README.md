# Ansible Role: Nginx Proxy Manager

Install Nginx Proxy Manager.  Includes local directory backups

## Requirements

This role assumes the following:

* Docker is installed

## Role Variables

### Main Variables

| Name | Details |
| --- | --- |
| `npm_version` | The version of the Docker container to use.  Available versions are [here](https://hub.docker.com/r/jc21/nginx-proxy-manager) |

### Default Variables

| Name | Default Value | Details |
| --- | --- | --- |
| `app_name` | `npm` | Used to name things |
| `app_folder` | `/apps/npm` | The base directory for deployment |

## Dependencies

None

## License

MIT
