### This is my practice of Ansible based on [Official BestPractice](https://docs.ansible.com/ansible/latest/user_guide/playbooks_best_practices.html)

# Directory

```
.
├ inventory
│   ├ production
│   │   ├ group_vars
│   │   │   ├ all.yml
│   │   │   ├ app.yml
│   │   │   ├ db.yml
│   │   │   └ web.yml
│   │   ├ hosts
│   │   └ host_vars
│   │       └ webserver.yml
│   └ staging
│       ├ group_vars
│       │   ├ all.yml
│       │   ├ app.yml
│       │   ├ db.yml
│       │   └ web.yml
│       ├ hosts
│       └ host_vars
├ playbook.yml
├ README.md
└ roles
    └ common
        ├ create_directory
        │   ├ defaults
        │   │   └ main.yml
        │   ├ files
        │   ├ handlers
        │   │   └ main.yml
        │   ├ meta
        │   │   └ main.yml
        │   ├ README.md
        │   ├ tasks
        │   │   └ main.yml
        │   ├ templates
        │   ├ tests
        │   │   ├ inventory
        │   │   └ test.yml
        │   └ vars
        │       └ main.yml
        ├ install_packages
        │   ├ defaults
        │   │   └ main.yml
        │   ├ files
        │   ├ handlers
        │   │   └ main.yml
        │   ├ meta
        │   │   └ main.yml
        │   ├ README.md
        │   ├ tasks
        │   │   └ main.yml
        │   ├ templates
        │   ├ tests
        │   │   ├ inventory
        │   │   └ test.yml
        │   └ vars
        │       └ main.yml
        └ set_chrony
            ├ defaults
            │   └ main.yml
            ├ files
            ├ handlers
            │   └ main.yml
            ├ meta
            │   └ main.yml
            ├ README.md
            ├ tasks
            │   └ main.yml
            ├ templates
            │   └ chrony.j2
            ├ tests
            │   ├ inventory
            │   └ test.yml
            └ vars
                └ main.yml
```
