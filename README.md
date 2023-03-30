# smart_lld_agent2
Monitorar o S.M.A.R.T dos seus discos (NVMe e HDD) via Zabbix

Ainda não testei em SSD SATA, não garanto que funcione corretamente.

Para instalar:

- Instale o Smartmontools (No terminal do Windows, digite: winget install smartmontools.smartmontools);
- Copie o arquivo userparameter_smartctl_rafael.conf para a pasta de plugins do seu Zabbix Agent;
- Importe o template (XML) no Zabbix;
- Atribua o template a um host.
