## Ansible Nullmailer

Simple Ansible-Module to install/manage a Nullmailer


```
  - role: pludoni.nullmailer
    nullmailer_remotes:
      - mail-intern.example.com smtp --port=587 --starttls --insecure --user=mail-sender --pass=Mail-Sender
    nullmailer_mailname: "{{ ansible_hostname }}"
    nullmailer_adminaddress: admin@example.com
    nullmailer_me: '$hostname.example.com'
```

