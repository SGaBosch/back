curl -fsSL https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.4/install.sh | bash
source ~/.bashrc  # vagy ~/.zshrc ha zsh-t használsz
# back

nvm install lts/iron
nvm use lts/iron
nvm alias default lts/iron


node -v
npm -v


corepack enable
yarn set version 4.4.1


yarn -v


sudo apt install -y docker.io
sudo systemctl enable --now docker


docker --version
git --version


npx @backstage/create-app@latest
