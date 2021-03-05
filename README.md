## Ansible / Ansible Tower - Minecraft Server Roles

### Project Status: Stable
Updates in ver 0.2:
  - `minecraft_svr_announce.yml` has been retired and is now a role titled `role/minecraft_svr_announce/`. An example of using this solution is found within `playbook-minecraft_svr_announce.yml`
  - `minecraft_svr_build.yml` has been retired and is now a role titled `role/minecraft_svr_prep/`. An example of using this solution is found within `playbook-minecraft_svr_prep.yml`. The justification for the name change was that `minecraft_svr_build.yml` was a misleading name.
  - `minecraft_svr_dl_rc.yml` has been retired and is now a rile titled `role/minecraft_svr_update_backup/`. An example of using this solution is found within `playbook-minecraft_svr_update_backup.yml`. The justification for the name change was that `minecraft_svr_dl_rc.yml` was a misleading name.

### Description
  - Repository contains Ansible code
  - The files `playbook-minecraft_*` contain examples of how to use the code within `roles/` 
  - These solutions are tested for use on `Ubuntu 18.04`
  - To run locally, first install python `sudo apt install python3-pip`
  - Next install ansible, `python3 -m pip install ansible`
  - Now run all of the above solutions against the `host: localhost` and `connection: local`

### Helpful Links
  - Offical Release of Minecraft Sever App: https://minecraft.net/en-us/download/server/
  - Setting Up A Server: https://minecraft.gamepedia.com/Tutorials/Setting_up_a_server
  - Download Minecraft Server Software: https://minecraft.net/en-us/download/server/
  - Ubuntu Server OS: https://www.ubuntu.com/download/server
