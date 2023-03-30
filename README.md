# Monitorar o S.M.A.R.T dos seus discos (NVMe e HDD) via Zabbix

Ainda não testei em SSD SATA, não garanto que funcione corretamente.
Não criei nenhum alerta, apenas a coleta dos dados, pois a ideia é usar em um PC pessoal.

# Para instalar:

- Instale o Smartmontools (No terminal do Windows, digite: winget install smartmontools.smartmontools);
- Copie o arquivo userparameter_smartctl_rafael.conf para a pasta de plugins do seu Zabbix Agent;
- Nesse arquivo, o caminho do Smartmontools está em C:\Program Files\Smartmontools\. Se seu Windows está em Português, não se preocupe, vai funcionar.
- Importe o template (XML) no Zabbix;
- Atribua o template a um host.



# S.M.A.R.T monitoring for NVMe and HDD on Zabbix

I have not tested this template in SSD, no guarantee that works.
I have not created the Triggers, because it's for personal porpouse only.

# To install:

- Install Smartmontools (In the Windows terminal, type: winget install smartmontools.smartmontools);
- Copy the userparameter_smartctl_rafael.conf file to your Zabbix Agent plugins folder;
- In this file, the Smartmontools path is at C:\Program Files\Smartmontools\. If your Windows is not in English, don't worry, it will work.
- Import the template (XML) in Zabbix;
- Assign the template to a host.
