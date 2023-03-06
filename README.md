# Development environment install
## Deb flavored Linux distros

Install Node with nvm:
```bash
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
```

Note: you need to launch a new terminal after installing nvm.

Install Node version:
```bash
nvm install 14
nvm use 14
```

Install jekyll:
```bash
sudo apt-get install ruby-full build-essential zlib1g-dev

echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc

gem install jekyll bundler
```

Install dependencies:
```bash
npm install
```

Run:
```bash
npm run dev
```

Sources:
- https://jekyllrb.com/docs/installation/ubuntu/
- https://github.com/nvm-sh/nvm