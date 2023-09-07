# headlamp

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/headlamp)
[![General Workflow](https://github.com/rolehippie/headlamp/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/headlamp/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/headlamp/actions/workflows/docs.yml/badge.svg)](https://github.com/rolehippie/headlamp/actions/workflows/docs.yml)
[![Galaxy Workflow](https://github.com/rolehippie/headlamp/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/headlamp/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/headlamp)](https://github.com/rolehippie/headlamp/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.headlamp-blue)](https://galaxy.ansible.com/rolehippie/headlamp)

> [!IMPORTANT]
> This role have been archived because of the lack of maintenance and because
> we are not actively using it anymore. If you are using this role feel free
> to fork and maintain it on your own. Maybe we will unarchive this repository
> in the future at some point, maybe not... Who knows...

Ansible role to install headlamp Kubernetes interface.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [headlamp_arch](#headlamp_arch)
  - [headlamp_package](#headlamp_package)
  - [headlamp_version](#headlamp_version)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`

## Default Variables

### headlamp_arch

Architecture for the package

#### Default value

```YAML
headlamp_arch: amd64
```

### headlamp_package

Download URL for the package to install

#### Default value

```YAML
headlamp_package: https://github.com/headlamp-k8s/headlamp/releases/download/v{{ headlamp_version
  }}/headlamp_{{ headlamp_version }}-1_{{ headlamp_arch }}.deb
```

### headlamp_version

Version for the package

#### Default value

```YAML
headlamp_version: 0.19.1
```

## Discovered Tags

**_headlamp_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
