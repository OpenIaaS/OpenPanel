<div align="center">
<a href="https://openpanel.co/">
    <img alt="website" src="/documentation/static/img/openpanel_admin.gif">
</a>
  
<br/>
<br/>

<div align="center">
    <a href="https://openpanel.co">Home Page</a> |
    <a href="https://community.openpanel.co/">Forums</a> |
    <a href="https://openpanel.co/docs/admin/intro/">Documentation</a>
</div>
</div>

<br/>
<br/>

<div align="center"> 
    
Deliver a <strong>VPS-like experience</strong> to your users at a fraction of the cost, with all-inclusive features such as <strong>resource limiting, user isolation, WP Manager, and enhanced security</strong> seamlessly integrated for worry-free hosting.

<br />
<br />

</div>
<br/>

## What is OpenPanel

OpenPanel is a powerful and flexible web hosting control panel for Linux systems. Available in an community-supported version, and a more feature-filled version with premium support, OpenPanel is the cost-effective and comprehensive solution to web hosting management.

**OpenPanel** offers a distinct advantage over other hosting panels by providing each user with an isolated environment and tools to fully manage it. This ensures that you enjoy full control over your environment, simillar to a VPS experience. You can effortlessly install new PHP versions, modify server configurations, view domain logs, restart services, and perform numerous other advanced tasks.

[![openpanel scheme](/documentation/static/img/admin/openpanel_scheme.png)](https://openpanel.co/docs/panel/intro/)

This panel is the culmination of years of experience in the hosting industry, having spent decades working with various hosting panels we made sure to include all features that simply make sense.

When we designed OpenPanel, we prioritized features that are not only user-friendly for beginners but also advanced enough to alleviate maintenance tasks for system administrators and hosting support teams.

Some of the unique features worth mentioning are:

- Users can run [Nginx or Apache webserver](https://openpanel.co/docs/admin/plans/hosting_plans/#list-hosting-plans).
- Users can [install PHP versions](https://openpanel.co/docs/panel/advanced/server_settings#install-php-version) they need, [edit php.ini files](https://openpanel.co/docs/panel/advanced/server_settings#phpini-editor) and set desired limits.
- Control [MySQL settings](https://openpanel.co/docs/panel/advanced/server_settings#mysql-settings), set limits, [enable remote mysql access](https://openpanel.co/docs/panel/databases/remote) and much more.
- [Update system services](https://openpanel.co/docs/panel/advanced/server_settings#service-status) and even install new services that they need.
- Manage WordPress websites easily with [WP Manager](https://openpanel.co/docs/panel/applications/wordpress).
- Password-less login to [phpMyAdmin](https://openpanel.co/docs/panel/databases/phpmyadmin) and [Web Terminal](https://openpanel.co/docs/panel/advanced/terminal).
- Built-in [REDIS](https://openpanel.co/docs/panel/caching/Redis) and [Memcached](https://openpanel.co/docs/panel/caching/Memcached) object caching.

## OpenPanel vs OpenAdmin


The **OpenAdmin** offers an administrator-level interface where you can efficiently handle tasks such as creating and managing users, setting up hosting plans, configuring backups, and editing OpenPanel settings.
The **OpenPanel** interface is the client-level panel where end-users can manage their enviroment, edit settings, install services, create websites and more.

[![openpanel-vs-openadmin](/documentation/static/img/admin/openpanel_vs_openadmin.svg)](https://openpanel.co/docs/admin/intro/)


## Supported OS

- Debian 12
- Debian 11
- Ubuntu 22
- Ubuntu 24 *(without quotas)
- RockyLinux 9.4 *(without quotas)

## Technology Stack


| OpenAdmin |  OpenPanel |
|------------------|---|
|         ![nginx](https://img.shields.io/badge/Nginx-1.22--1.26-blue?logo=nginx&logoColor=white) ![ssl](https://img.shields.io/badge/Let'sEncrypt-green?logo=letsencrypt&logoColor=white) ![docker](https://img.shields.io/badge/Docker-blue?logo=docker&logoColor=white) ![modsec](https://img.shields.io/badge/ModSecurity-WAF-blue?logo=modsecurity&logoColor=white)        |  ![apache](https://img.shields.io/badge/Apache-2.4-7aba03?logo=apache&logoColor=white) ![mysql](https://img.shields.io/badge/MySQL-5.5--8.2-blue?logo=mysql&logoColor=white) ![memcached](https://img.shields.io/badge/Memcached-1.4--1.6-blue) ![nginx](https://img.shields.io/badge/Nginx-1.22--1.26-blue?logo=nginx&logoColor=white) ![redis](https://img.shields.io/badge/Redis-3.0--7.2-blue?logo=redis&logoColor=white) ![php](https://img.shields.io/badge/PHP-5.4--8.3-blue?logo=php&logoColor=white) ![nvm](https://img.shields.io/badge/NVM-1.1.12-7aba03?logo=node.js&logoColor=white) ![python](https://img.shields.io/badge/Python-3.8--3.12-blue?logo=python&logoColor=white) ![phpmyadmin](https://img.shields.io/badge/PHPMyAdmin-6.5-bluelogo=phpmyadmin&logoColor=white) |

## What do you mean by "open" ?

Open for business!

OpenPanel is **not** open-source. The primary reason behind this decision is our commitment to maintaining the highest standards of security for our users. Here are the key reasons:

1. **Enhanced Security**:
    - Keeping OpenPanel closed-source significantly reduces the risk of exposing vulnerabilities. By limiting access to the source code, we can better protect our users from potential security threats and malicious attacks.

2. **Controlled Access**:
    - A closed-source model allows us to strictly control who can view and modify the code. This minimizes the risk of unauthorized changes or contributions that could introduce security flaws.

3. **Integrity and Trustworthiness**:
    - Ensuring the integrity of our software is paramount. By maintaining a closed-source environment, we can guarantee that every release of OpenPanel has undergone thorough security reviews and testing, providing our users with a trustworthy solution.

While OpenPanel itself is not 100% open source, we are committed to transparency and security.

We regularly conduct internal audits, apply the latest security patches, and follow industry best practices to safeguard our users' data.

## Installation

To install on self-hosted VPS/Dedicated server: 

```bash
bash <(curl -sSL https://get.openpanel.co/)`
```

To configure server on installation, please visit: https://openpanel.co/install 

----

Spin a 1-click droplet on DigitalOcean: 

[![droplet](/documentation/static/img/do-btn-blue.svg)](https://marketplace.digitalocean.com/apps/openpanel?refcode=6498bfc47cd6&action=deploy)


DigitalOcean API:
```bash
curl -X POST -H 'Content-Type: application/json' \
     -H 'Authorization: Bearer '$TOKEN'' -d \
    '{"name":"choose_a_name","region":"nyc3","size":"s-2vcpu-4gb","image":"openpanel"}' \
    "https://api.digitalocean.com/v2/droplets"
```

## Support

Our [Community](https://community.openpanel.co/) serves as our virtual Headquater, where the community helps each other.

**Learn, share** and **discuss** with other community members your questions.
