# How to set up
```
ansible-playbook -i hosts site.yml -c local -K
```

TODO:
- Configure aws
- Configure drive
- Configure repos
- Configure bashrc
- Configure docker as sudo (https://docs.docker.com/engine/install/linux-postinstall/)
- Install black
```
source ~/.vim/black/bin/activate  # make sure to install in the right venv
pip install --upgrade git+https://github.com/psf/black.git
```
- Configure dbeaver
