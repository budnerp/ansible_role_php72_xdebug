# Ansible role for Xdebug
Ansible role for Xdebug for PHP 7.2

## What's inside?
1. Interesting PHP dirs and files: 
    ```
    /etc/opt/remi/php72/php.d/15-xdebug.ini
    ```
2. Custom settings as per defaults/main.yml
   
## Tested on

## Installation
1. Navigate to Ansible's roles folder
2. Add the repo to git modules
    ```
    git submodule add https://github.com/budnerp/ansible_role_php72_xdebug.git ansible_role_php72_xdebug
    ```
3. Add the role to Ansible's playbook file
    ```    
    roles:
    [...]
        - ansible_role_php72_xdebug
    [...]
    ```

## Other links
- [https://xdebug.org/]()
- [http://pecl.php.net/package/xdebug]()
- [https://blog.remirepo.net/pages/PECL-extensions-RPM-status]()

## TO DO
-[ ] add dependencies 
-[ ] check profiler and add defaults

## License
Copyright (c) We Are Interactive under the MIT license.