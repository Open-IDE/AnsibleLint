# AnsibleLint
Home: - doc: https://ansible.readthedocs.io/projects/lint/

I Love this tool!

# Changed Rules
The only rule I want to change is: ["avoid using paths when importing roles"](https://ansible.readthedocs.io/projects/lint/rules/role-name/) This is because most Uni projects use Subfolders to organize roles and also name them TitleCase like objects, as we have a high emphasis on organization & readability.

For ex:
```
  roles:
    - AptCacherNg/Client
    - Gnome/minimal
```
