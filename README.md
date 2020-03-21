# Setup local laptop

## Usage

# sudo apt-get install software-properties-common - probably not needed
#sudo apt-add-repository ppa:ansible/ansible
sudo apt-get update
sudo apt-get install ansible
sudo apt-get install git

sudo ansible-pull -U https://github.com/saretter/ansible-client.git -i localhost local.yml --extra_vars="user=<your_user_name>"

