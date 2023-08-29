# MULTI-PORT
apt --fix-missing update && apt update && apt upgrade -y && apt install -y wget screen && wget -q https://raw.githubusercontent.com/scscp/MULTI-PORT/main/setup.sh && chmod +x setup.sh && screen -S setup ./setup.sh
