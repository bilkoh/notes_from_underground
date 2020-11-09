# Install from source
~~~ Shell
git clone https://github.com/fish-shell/fish-shell.git
cd fish-shell; cmake .; make; sudo make install
sudo apt install cmake
cmake .
make
sudo make install
~~~

# Make default
~~~ Shell
echo /usr/local/bin/fish | sudo tee -a /etc/shells
chsh -s /usr/local/bin/fish
~~~

# Install theme
~~~ Shell
curl -L https://get.oh-my.fish | fish
omf install bira
omf theme bira
~~~
