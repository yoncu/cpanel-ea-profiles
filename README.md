# cpanel-ea-profiles

Install:
```
mkdir -p /etc/cpanel/ea4/profiles/custom/;
curl https://raw.githubusercontent.com/yoncu/cpanel-ea-profiles/main/cpanel-ea-profiles.json>/etc/cpanel/ea4/profiles/custom/yoncu-bilisim.json;
/usr/local/bin/ea_install_profile --install /etc/cpanel/ea4/profiles/custom/yoncu-bilisim.json;
```
