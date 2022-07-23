
# Install the love ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_love

# Clone the love ansible role. 
git clone git@github.com:computate-org/computate_love.git ~/.ansible/roles/computate.computate_love

# Change into the love ansible role directory. 
cd ~/.ansible/roles/computate.computate_love
```

# Run the love ansible playbook to install love locally. 

```bash
ansible-playbook install.yml
```

Christopher Tate
