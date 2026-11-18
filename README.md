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

You can see a brief summary on the philosophy of Pacifism in `pacifism.txt` – I suggest you give it a look.

Despite the writing, there is nothing Pacifist about the shell script. The name developed like this:

pathy -> pathifist (play on the words path and pacifist) -> pacifist

I only chose the name Pacifist to follow the theme I set with [Nihilist](https://github.com/Centurion774477/Nihilist).

<hr>

Thanks for giving Pacifist a look.

Cheers!
