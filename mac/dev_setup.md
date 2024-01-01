/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

brew install visual-studio-code google-chrome

brew install --cask alfred bettertouchtool

brew install --cask intellij-idea slack pop
brew install direnv rover
brew install awscli gh java libpq python
python3 -m ensurepip --upgrade

brew install --cask docker
sudo ln -s ~/Library/Containers/com.docker.docker/Data/docker.raw.sock /var/run/docker.sock
brew install kubectl kops stern docker docker-compose docker-credential-helper docker-gen docker-credential-helper-ecr docker-ls docker-machine

brew install volta jq yq

volta install node

brew install google-cloud-sdk helm

pip3 install meltano

# gcloud components install gke-gcloud-auth-plugin

# helm plugin install https://github.com/databus23/helm-diff

brew install --cask google-drive

# color picker

brew install --cask pika

# personal stuff

brew install --cask spotify
