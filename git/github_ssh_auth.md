# Set up github ssh auth
~~~ Shell
cat > ~/.ssh/id_ed25519

    -----BEGIN OPENSSH PRIVATE KEY-----
    *
    -----END OPENSSH PRIVATE KEY-----

chmod 600 ~/.ssh/id_ed25519

eval $(ssh-agent -s)
    Agent pid 573311

ssh-add ~/.ssh/id_ed25519

ssh -T git@github.com
~~~

## note
Requires switch to ssh scheme from HTTPS

Eg: `https://github.com/bilkoh/` to `git@github.com:bilkoh/`

~~~ Shell
git remote add origin https://github.com/bilkoh/notes_from_underground.git
~~~
Should be
~~~ Shell
git remote add origin git@github.com:bilkoh/notes_from_underground.git
~~~


