httpd [![Build Status](https://travis-ci.org/xcezx/ansible-httpd.svg)](https://travis-ci.org/xcezx/ansible-httpd)
========

install and configuration httpd

Role Variables
--------------

- `httpd_install_packages`
- `httpd_ServerTokens`
- `httpd_ServerRoot`
- `httpd_PidFile`
- `httpd_Timeout`
- `httpd_KeepAlive`
- `httpd_MaxKeepAliveRequests`
- `httpd_KeepAliveTimeout`
- `httpd_prefork_StartServers`
- `httpd_prefork_MinSpareServers`
- `httpd_prefork_MaxSpareServers`
- `httpd_prefork_ServerLimit`
- `httpd_prefork_MaxClients`
- `httpd_prefork_MaxRequestsPerChild`
- `httpd_worker_StartServers`
- `httpd_worker_MaxClients`
- `httpd_worker_MinSpareThreads`
- `httpd_worker_MaxSpareThreads`
- `httpd_worker_ThreadsPerChild`
- `httpd_worker_MaxRequestsPerChild`
- `httpd_Listen`
- `httpd_ErrorLog`
- `httpd_LogLevel`
- `httpd_ServerAdmin`
- `httpd_ServerName`
- `httpd_ExtendedStatus`
- `httpd_UseCanonicalName`
- `httpd_ServerSignature`
- `httpd_DirectoryIndex`
- `httpd_AccessFileName`
- `httpd_HostnameLookups`
- `httpd_TraceEnable`
- `httpd_ServerAdmin`
- `httpd_CustomLogFormats`
- `httpd_LoadModules`

Example Playbook
-------------------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: xcezx.httpd }

License
-------

BSD
