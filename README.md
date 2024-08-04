# Gaia_node_guide
sudo apt update -y
sudo apt-get update
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
source ~/.bashrc
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/qwen2-0.5b-instruct/config.json
gaianet start #Copy the link of our node
gaianet info  #Next, insert this command and get the Node id and Device id — copy and save to a safe place
