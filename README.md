# Pacifist

I love writing software, but I always dread the moment where I have to add the script/binary to my PATH.

That's why I made Pacifist — you can add a script to your PATH with two words and get back to the important things.

# Install Pacifist

To install Pacifist, you can run:
```
curl -fsSL https://raw.githubusercontent.com/Centurion774477/Pacifist/refs/heads/main/pacifist > pacifist && chmod +x pacifist && mv pacifist ~/.local/bin/ && echo "Done!"
```

Make sure you have `curl` installed.

You'll also need `~/.local/bin` to both exist and be on your path.
If it doesn't exist, run `mkdir -p ~/.local/bin`.
If it's not on your PATH, add this to your shell config file (.bashrc, .zshrc, etc.):
`export PATH=\"\$HOME/.local/bin:\$PATH\"`.

# Pacifism

You can see a brief writing on the philosophy of Pacifism in `pacifism.txt` – I suggest you give it a look.

Cheers!
