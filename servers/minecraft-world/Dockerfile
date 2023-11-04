FROM itzg/minecraft-server:latest

ENV VERSION='1.20.2'

# Configure Server with Default Values
ENV   EULA='TRUE' \
      TYPE='PURPUR' \
      ONLINE_MODE='FALSE' \
      ANNOUNCE_PLAYER_ACHIEVEMENTS='FALSE' \
      MAX_PLAYERS=50 \
      MEMORY='2G' \
      MOTD="Welcome to Glue Eaters Anonymous' Minecraft Server" \
      VIEW_DISTANCE='32' \
      COPY_CONFIG_DEST=/data \
      COPY_CONFIG_SRC=resources/config \
      ENFORCE_WHITELIST='TRUE' \
      OPS=nadrojisk,ComradeYuri96

RUN mkdir /data/world/; chown minecraft:minecraft /data/world/
