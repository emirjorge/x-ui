# X-UI

ESPAÑOL  
X-UI es un panel webUI basado en Xray-core que admite múltiples protocolos y múltiples usuarios.
Este proyecto es un fork de [vaxilu&#39;s project](https://github.com/vaxilu/x-ui),y es un proyecto experimental que utilicé para aprender.
If you need more language options ,please open a issue and let me know that

# Changes   
- 2023.07.18：Aletatorio Reality dest y serverNames; configuraciones de rastreo más detalladas disponibles  
- 2023.06.10：Habilitar TLS reutilizará los certificados y el dominio del panel; agregará configuración para ocspStapling; refactorizará el límite de dispositivos.
- 2023.04.09：Support REALITY for now  
- 2023.03.05：User expiry time limit for each user  
- 2023.02.09：User traffic limit for each user,support utls sharing link  
- 2022.12.07：Add device limit and more tls configuration  
- 2022.11.15：Add xtls-rprx-vision flow option;cron job for geo update and log clear    
- 2022.10.23：Fully support for English,add export links,add CPU cores display
- 2022.08.11：Support multi users on the same port;add CPU limit exceed  alert  
- 2022.07.28：Add acme standalone mode for cert issue；add  mechanism to keep X-UI alive even there exist crashes
- 2022.07.24：Add base path auto generate feature for security;add traffice reset automatically;add device alert
- 2022.07.21：Add more translations;add restart/stop xray service in Web panel
- 2022.07.11：Add time expiration notify for each inbound;add traffic limit notify for each inbound;add get url link command/inbound copy command in telegram bot  
- 2022.07.03：Add transport options in Trojan protocol;restruct Telegram bot for convenience  
- 2022.06.19：Add shadowsocks 2022 Ciphers,add inbounds search,traffic clear function in WebUI
- 2022.05.14：Add Telegram bot commands,support enable/disable/delete/status check
- 2022.04.25：Add SSH login notify
- 2022.04.23：Add WebUi login notify
- 2022.04.16：Add Telegram bot set up in WebUi pannel
- 2022.04.12：Optimize Telegram bot notify,more human friendly
- 2022.04.06：Add cert issue function，optimize installation/update and add telegram bot notify

# Basics

- support system status info check
- support multi protocols and multi users
- support protocols：vmess、vless、trojan、shadowsocks、dokodemo-door、socks、http
- support many transport method including tcp、udp、ws、kcp etc
- traffic counting,traffic restrict and time restrcit
- support custom configuration template
- support https access fot WebUI
- support SSL cert issue by Acme
- support telegram bot notify and control
- more functions in control menu  

# Installation
Asegúrese de que su sistema esta instalado `bash`, `curl` y `network`, procedemos...

Para usuarios chinos, utilice el siguiente comando para instalar la versión compatible con idioma chino:
```
bash <(curl -Ls https://raw.githubusercontent.com/emirjorge/x-ui/master/install.sh)
```  
Para usuarios de idioma inglés, utilice el siguiente comando para instalar la versión compatible con inglés:
```
bash <(curl -Ls https://raw.githubusercontent.com/emirjorge/x-ui/master/install_en.sh)
``` 

## Shortcut  
After Installation，you can input `x-ui`to enter control menu，current menu details：
```
 
  x-ui control menu
  0. exit
————————————————
  1. install   x-ui
  2. update    x-ui
  3. uninstall x-ui
————————————————
  4. reset username
  5. reset panel
  6. reset panel port
  7. check panel info
————————————————
  8. start x-ui
  9. stop  x-ui
  10. restart x-ui
  11. check x-ui status
  12. check x-ui logs
————————————————
  13. enable  x-ui on sysyem startup
  14. disabel x-ui on sysyem startup
————————————————
  15. enable bbr 
  16. issuse certs
 
x-ui status: running
enable on system startup: yes
xray status: running

please input a legal number[0-16]: 
```

# System requirements:  
## MEM  
- 128MB minimal/256MB+ recommend  
## OS
- CentOS 7+
- Ubuntu 16+
- Debian 8+

# Credits
- [vaxilu/x-ui](https://github.com/vaxilu/x-ui)
- [XTLS/Xray-core](https://github.com/XTLS/Xray-core)
- [telegram-bot-api](https://github.com/go-telegram-bot-api/telegram-bot-api) 
- [FranzKafkaYu Repositorio](https://github.com/FranzKafkaYu/x-ui)

# Sponsor  

if you want to purchase some virtual servers,you can purchase by my aff link:   
- [BandwagonHost](https://bandwagonhost.com/aff.php?aff=65703)     
- [Cloudcone](https://app.cloudcone.com/?ref=7536)  
- [SpartanHost](https://billing.spartanhost.net/aff.php?aff=1875)  


