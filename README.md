# Ansible Role: Monica

An Ansible role to run [Monica](https://github.com/monicahq/monica) via Docker containers.

## Requirements

This role assumes the following:

* You have Docker installed
* You will manage backups

## Role Variables

## Main Variables

| Name | Details |
| --- | --- |
| `monica_version` | The version of the Monica Dockerfile to use. More versions available [here]() |
| `monica_database_password` | The user password for the DB |

## Default Variables

| Name | Default Value | Details |
| --- | --- | --- |
| `app_name` | `monica` | Used to name things |
| `app_folder` | `/apps/monica` | The base directory for deployment |
| `monica_database_username` | `monica` | Database username |

## Dependencies

None

## License

MIT
