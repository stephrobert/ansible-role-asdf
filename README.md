# stephrobert.asdf

[![Ansible version](https://img.shields.io/badge/ansible-%3E%3D2.10-black.svg?style=flat-square&logo=ansible)](https://github.com/ansible/ansible)

⭐ Star us on GitHub — it motivates us a lot!

Install asdf

**Platforms Supported**:

| Platform | Versions |
|----------|----------|
| Debian | bullseye, bookworm |
| Ubuntu | jammy |

## ⚠️ Requirements

Ansible >= 2.11.

### Ansible role dependencies

None.

## ⚡ Installation

### Install with Ansible Galaxy

```shell
ansible-galaxy install stephrobert.asdf
```

### Install with git

If you do not want a global installation, clone it into your `roles_path`.

```bash
git clone   stephrobert.asdf
```

But I often add it as a submodule in a given `playbook_dir` repository.

```bash
git submodule add  roles/stephrobert.asdf
```

As the role is not managed by Ansible Galaxy, you do not have to specify the
github user account.

### ✏️ Example Playbook

Basic usage is:

```yaml
- hosts: all
  roles:
    - role: stephrobert.asdf
```

## ⚙️ Role Variables

Variables are divided in three types.

The **default vars** section shows you which variables you may
override in your ansible inventory. As a matter of fact, all variables should
be defined there for explicitness, ease of documentation as well as overall
role manageability.

The **context variables** are shown in section below hint you
on how runtime context may affects role execution.

### Default variables
Role default variables from `defaults/main.yml`.


### Context variables

Those variables from `vars/*.{yml,json}` are loaded dynamically during task
runtime using the `include_vars` module.

Variables loaded from `vars/main.yml`.




## Author Information

none