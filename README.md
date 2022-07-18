# Ansible-Warframe


setup using pip     

mkdir -p ~/.local/bin
echo 'PATH=$PATH:~/.local/bin' >> ~/.bashrc
source ~/.bashrc
## install pip3
sudo apt install python3-pip -y
## install ansible with pip3
pip3 install --user ansible
# check that ansible has been installed
ansible --version

copied ngninx
ansible 127.0.0.1 -m apt -a "name=nginx state=present update_cache=true" --become

curl http://localhost

-must be run again
ansible 127.0.0.1 -m apt -a "name=nginx state=present update_cache=true" --become