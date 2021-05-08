# FMO - minecraft_server
### Gabriel Morejón López
@elgabo82 - gabrielmorejon@gmail.com | gabriel@grupofmo.com
### Gabriel Morejón Obregón
### Leandro Morejón Obregón
### Renata Morejón Obregón

Referencias: https://minecraft.fandom.com/wiki/Tutorials/Setting_up_a_server


# Instrucciones

Añadir un usuario y grupo llamado "Minecraft": groupadd minecraft
Crear el usuario: useradd --system --shell /usr/sbin/nologin --home /opt/minecraft -g minecraft minecraft

Copiar el script minecraft-server.sh como /etc/systemd/system/minecraft@.service
