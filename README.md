# Zabbix Icons Installation Guide

This guide explains how to install custom icons for Zabbix/Grafana dashboards.

## Installation Steps

1. Create a logos directory in Grafana's public images folder:
```bash
mkdir /usr/share/grafana/public/img/logos
```

2. Navigate to the logos directory:
```bash
cd /usr/share/grafana/public/img/logos
```

3. Clone the repository:
```bash
git clone https://github.com/rpradx/zabbix.git
```

4. Move icons to the logos directory:
```bash
cd zabbix/Pack-Icons/
mv *.png /usr/share/grafana/public/img/logos/
```

After following these steps, the icons will be available for use in your Grafana dashboards.