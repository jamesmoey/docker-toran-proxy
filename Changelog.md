# Changelog

**latest**
- Update image FROM to cedvan/ubuntu:14.04.20150414
- Add ssh config for root user

**1.1.6-2**
- Add **cron** every minute for download packages in background
- Fix toran config `git_path`
- Optimize logs directories

**1.1.6-1**
- Download Toran Proxy in Dockerfile
- Move save data in `/data/toran-proxy`
- Add default config for *git* and save mirrors in /data
- Rename `settings.yml` to `config.yml`
- Remove useless `parameters.yml`
- Move `assets/config` to `/assets/config` in container
- Remove useless `init.sh`
- Remove useless configuration *TORAN_PACKAGIST*, may change with toran interface
- Remove useless configuration *TORAN_SYNC*, may change with toran interface

**1.1.6**
- First version
