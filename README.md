# Manual de instalação

Clone o repositório

    git clone git@github.com:Brunozrk/ansible-rails.git

Copie o arquivo /ansible/hosts.sample para /ansible/hosts, colocando as configurações do seu servidor.

Considerando que o Python esteja instalado. Instale o pip e o ansible

    sudo easy_install pip
    sudo pip install ansible

Para provisionar o ambiente, execute o arquivo playbook.yml

    ansible-playbook -i hosts playbook.yml
