# Ansible Role: Nginx Proxy Manager

Install Nginx Proxy Manager.  Includes local directory backups

## Requirements

This role assumes the following:

* Docker is installed

## Role Variables

| Name | Default Value | Details |
| --- | --- | --- |
| `npm_version` | `latest` | The version of the Docker container to use.  Available versions are [here](https://hub.docker.com/r/jc21/nginx-proxy-manager) |
| `npm_admin_port` | 9001 | The port from which you can access the NPM admin site |
| `app_name` | `npm` | Used to name things |
| `app_folder` | `/apps/npm` | The base directory for deployment |

## Dependencies

None

## License

MIT
