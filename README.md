[![logo](https://raw.githubusercontent.com/metwork-framework/resources/master/logos/metwork-white-logo-small.png)](http://www.metwork-framework.org)

# MetWork Framework GitHub repositories index

This repository is a just a README to introduce all [Metwork Framework GitHub repositories](https://github.com/metwork-framework).

## Main modules

| Module | Description | CI (master) | CI (integration)
| --- | --- | --- | ---
| [mfext](https://github.com/metwork-framework/mfext) | Dependency module which provides plenty of recent opensource softwares | [![Drone CI](http://metwork-framework.org:8000/api/badges/metwork-framework/mfext/status.svg)](http://metwork-framework.org:8000/metwork-framework/mfext) | [![Drone CI](http://metwork-framework.org:8000/api/badges/metwork-framework/mfext/status.svg?branch=integration)](http://metwork-framework.org:8000/metwork-framework/mfext)
| [mfserv](https://github.com/metwork-framework/mfserv) | Webservices module | [![Drone CI](http://metwork-framework.org:8000/api/badges/metwork-framework/mfserv/status.svg)](http://metwork-framework.org:8000/metwork-framework/mfserv) | [![Drone CI](http://metwork-framework.org:8000/api/badges/metwork-framework/mfserv/status.svg?branch=integration)](http://metwork-framework.org:8000/metwork-framework/mfserv)
| [mfdata](https://github.com/metwork-framework/mfdata) | "Incoming files" processing framework | [![Drone CI](http://metwork-framework.org:8000/api/badges/metwork-framework/mfdata/status.svg)](http://metwork-framework.org:8000/metwork-framework/mfdata) | [![Drone CI](http://metwork-framework.org:8000/api/badges/metwork-framework/mfdata/status.svg?branch=integration)](http://metwork-framework.org:8000/metwork-framework/mfdata)
| [mfbase](https://github.com/metwork-framework/mfbase) | "Geospatial ready" storage framework | [![Drone CI](http://metwork-framework.org:8000/api/badges/metwork-framework/mfbase/status.svg)](http://metwork-framework.org:8000/metwork-framework/mfbase) | [![Drone CI](http://metwork-framework.org:8000/api/badges/metwork-framework/mfbase/status.svg?branch=integration)](http://metwork-framework.org:8000/metwork-framework/mfbase)
| [mfadmin](https://github.com/metwork-framework/mfadmin) | Monitoring module | [![Drone CI](http://metwork-framework.org:8000/api/badges/metwork-framework/mfadmin/status.svg)](http://metwork-framework.org:8000/metwork-framework/mfadmin) | [![Drone CI](http://metwork-framework.org:8000/api/badges/metwork-framework/mfadmin/status.svg?branch=integration)](http://metwork-framework.org:8000/metwork-framework/mfadmin)
| [mfsysmon](https://github.com/metwork-framework/mfsysmon) | System monitoring client module | [![Drone CI](http://metwork-framework.org:8000/api/badges/metwork-framework/mfsysmon/status.svg)](http://metwork-framework.org:8000/metwork-framework/mfsysmon) | [![Drone CI](http://metwork-framework.org:8000/api/badges/metwork-framework/mfsysmon/status.svg?branch=integration)](http://metwork-framework.org:8000/metwork-framework/mfsysmon)

## mfext addons

| Addon | Description | CI (master) | CI (integration)
| --- | --- | --- | ---
| [mfextaddon_scientific](https://github.com/metwork-framework/mfextaddon_scientific) | mfext addon for scientific libraries and tools | [![Drone CI](http://metwork-framework.org:8000/api/badges/metwork-framework/mfextaddon_scientific/status.svg)](http://metwork-framework.org:8000/metwork-framework/mfextaddon_scientific) | [![Drone CI](http://metwork-framework.org:8000/api/badges/metwork-framework/mfextaddon_scientific/status.svg?branch=integration)](http://metwork-framework.org:8000/metwork-framework/mfextaddon_scientific)
| [mfextaddon_python3_ia](https://github.com/metwork-framework/mfextaddon_python3_ia) | mfext addon for deep learning/IA libraries and tools for Python3 | [![Drone CI](http://metwork-framework.org:8000/api/badges/metwork-framework/mfextaddon_python3_ia/status.svg)](http://metwork-framework.org:8000/metwork-framework/mfextaddon_python3_ia) | [![Drone CI](http://metwork-framework.org:8000/api/badges/metwork-framework/mfextaddon_python3_ia/status.svg?branch=integration)](http://metwork-framework.org:8000/metwork-framework/mfextaddon_python3_ia)
| [mfextaddon_mapserver](https://github.com/metwork-framework/mfextaddon_mapserver) | mfext addon which provides [Mapserver software](https://mapserver.org) and libraries around ([mapserverapi](https://github.com/metwork-framework/mapserverapi)) and [mapserverapi_python](https://github.com/metwork-framework/mapserverapi_python)) | [![Drone CI](http://metwork-framework.org:8000/api/badges/metwork-framework/mfextaddon_mapserver/status.svg)](http://metwork-framework.org:8000/metwork-framework/mfextaddon_mapserver) | [![Drone CI](http://metwork-framework.org:8000/api/badges/metwork-framework/mfextaddon_mapserver/status.svg?branch=integration)](http://metwork-framework.org:8000/metwork-framework/mfextaddon_mapserver)
| [mfextaddon_vim](https://github.com/metwork-framework/mfextaddon_vim) | mfext addon which provides an opinionated vim editor (with configuration) | [![Drone CI](http://metwork-framework.org:8000/api/badges/metwork-framework/mfextaddon_vim/status.svg)](http://metwork-framework.org:8000/metwork-framework/mfextaddon_vim) | [![Drone CI](http://metwork-framework.org:8000/api/badges/metwork-framework/mfextaddon_vim/status.svg?branch=integration)](http://metwork-framework.org:8000/metwork-framework/mfextaddon_vim)

## docker build images

| Addon | Description |
| --- | --- |
| [docker-mfext-centos6-buildimage](https://github.com/metwork-framework/docker-mfext-centos6-buildimage) | the docker image used by CI to build mfext module on centos6 |
| [docker-mfext-centos7-buildimage](https://github.com/metwork-framework/docker-mfext-centos7-buildimage) | the docker image used by CI to build mfext module on centos7 |
| [docker-mfxxx-centos6-buildimage](https://github.com/metwork-framework/docker-mfxxx-centos6-buildimage) | the docker image used by CI to build mfxxx modules (not mfext) module on centos6 |
| [docker-mfxxx-centos7-buildimage](https://github.com/metwork-framework/docker-mfxxx-centos7-buildimage) | the docker image used by CI to build mfxxx modules (not mfext) module on centos7 |
| [docker-mfxxx-centos6-testimage](https://github.com/metwork-framework/docker-mfxxx-centos6-testimage) | the docker image used by CI to run integration tests for mfxxx modules (not mfext) module on centos6 |
| [docker-mfxxx-centos7-testimage](https://github.com/metwork-framework/docker-mfxxx-centos7-testimage) | the docker image used by CI to un integration tests for mfxxx modules (not mfext) module on centos7 |
| [docker-mfservplugins-centos7-buildimage](https://github.com/metwork-framework/docker-mfservplugins-centos7-buildimage) | a docker image used by CI to build some custom mfserv plugins |
| [docker-portable-envtpl-buildimage](https://github.com/metwork-framework/docker-portable-envtpl-buildimage) | a docker image to build a portable [https://github.com/metwork-framework/envtpl](envtpl) binary |
| [docker-mfextaddon_python3_ia-centos7-buildimage](https://github.com/metwork-framework/docker-mfextaddon_python3_ia-centos7-buildimage) | a docker image to build [https://github.com/metwork-framework/mfextaddon_python3_ia](python3_ia mfext addon) on centos7 |

## libs

| Repository | Description | CI (master) |
| --- | --- | --- |
| [mfutil_c](https://github.com/metwork-framework/mfutil_c) | xxx | [![Drone CI](http://metwork-framework.org:8000/api/badges/metwork-framework/mfutil_c/status.svg)](http://metwork-framework.org:8000/metwork-framework/mfutil_c) |
| [mfutil_lua](https://github.com/metwork-framework/mfutil_lua) | xxx | FIXME |
| [mfutil](https://github.com/metwork-framework/mfutil_lua) | xxx | [![GitHub CI](https://github.com/metwork-framework/mfutil/workflows/CI/badge.svg?branch=master)](https://github.com/metwork-framework/mfutil/actions?query=workflow%3ACI&branch=master) |

- [mapserverapi](https://github.com/metwork-framework/mapserverapi)
- [mapserverapi_python](https://github.com/metwork-framework/mapserverapi_python)
- [jsonlog2elasticsearch](https://github.com/metwork-framework/jsonlog2elasticsearch) => FIXME: to replace with jsonsyslog2elasticsearch
- [circus_autorestart_plugin](https://github.com/metwork-framework/circus_autorestart_plugin)
- [aiohttp_github_helpers](https://github.com/metwork-framework/aiohttp_github_helpers)
- [cronwrapper](https://github.com/metwork-framework/cronwrapper)
- [telegraf-unixsocket-python-client](https://github.com/metwork-framework/telegraf-unixsocket-python-client)
- [layerapi2](https://github.com/metwork-framework/layerapi2)
- mflog (FIXME)
- opininonated_configparser (FIXME)

## Jinja2 extensions 

| Repository | Description | CI (master) |
| --- | --- | --- |
| [jinja2_fnmatch_extension](https://github.com/metwork-framework/jinja2_fnmatch_extension) | xxx | [![GitHub CI](https://github.com/metwork-framework/jinja2_fnmatch_extension/workflows/CI/badge.svg?branch=master)](https://github.com/metwork-framework/jinja2_fnmatch_extension/actions?query=workflow%3ACI&branch=master) |
| [jinja2_from_json_extension](https://github.com/metwork-framework/jinja2_from_json_extension) | xxx | [![Drone CI](http://metwork-framework.org:8000/api/badges/metwork-framework/jinja2_from_json_extension/status.svg)](http://metwork-framework.org:8000/metwork-framework/jinja2_from_json_extension) |
| [jinja2_shell_extension](https://github.com/metwork-framework/jinja2_shell_extension) | xxx | [![GitHub CI](https://github.com/metwork-framework/jinja2_shell_extension/workflows/CI/badge.svg?branch=master)](https://github.com/metwork-framework/jinja2_shell_extension/actions?query=workflow%3ACI&branch=master) |
| [jinja2_getenv_extension](https://github.com/metwork-framework/jinja2_getenv_extension) | xxx | [![GitHub CI](https://github.com/metwork-framework/jinja2_getenv_extension/workflows/CI/badge.svg?branch=master)](https://github.com/metwork-framework/jinja2_getenv_extension/actions?query=workflow%3ACI&branch=master) |

## forked (but maintained) repos

- [deploycron](https://github.com/metwork-framework/deploycron)
- [envtpl](https://github.com/metwork-framework/envtpl)
- [lua-resty-statsd](https://github.com/metwork-framework/lua-resty-statsd)
- [cookiecutter](https://github.com/metwork-framework/cookiecutter)
- [auto-changelog](https://github.com/metwork-framework/auto-changelog)

## misc tools

- [linux_distributions_dependencies_checker](https://github.com/metwork-framework/linux_distributions_dependencies_checker)
- [linux_distributions_integration_tests](https://github.com/metwork-framework/linux_distributions_integration_tests)

## repositories specific to MetWork Framework

### custom addons

- [cookiecutter_hooks](https://github.com/metwork-framework/cookiecutter_hooks)
- [docker-drone-downstream-specific-image](https://github.com/metwork-framework/docker-drone-downstream-specific-image)
- [docker-drone-docker-specific-image](https://github.com/metwork-framework/docker-drone-docker-specific-image)

### mfserv plugins

- [github_organization_dashboard](https://github.com/metwork-framework/github_organization_dashboard)
- [github_webhook_pr_labelling](https://github.com/metwork-framework/github_webhook_pr_labelling)
- [generate_changelogs](https://github.com/metwork-framework/generate_changelogs)
- [github_copy_integration_branch](https://github.com/metwork-framework/github_copy_integration_branch)
- [github_force_common_files](https://github.com/metwork-framework/github_force_common_files)
- [github_webhook_issue_labelling](https://github.com/metwork-framework/github_webhook_issue_labelling)
- [github_webhook_no_pullrequest_on_master](https://github.com/metwork-framework/github_webhook_no_pullrequest_on_master)
- [public-website](https://github.com/metwork-framework/public-website)

### misc

- [index](https://github.com/metwork-framework/index)
- [external_sources](https://github.com/metwork-framework/external_sources)
- [docker-envtpl-runimage](https://github.com/metwork-framework/docker-envtpl-runimage)
- [quickstart](https://github.com/metwork-framework/quickstart) 
