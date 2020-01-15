
```console
# base
sudo pacman -S code ocaml opam #Arch Linux
sudo dnf install code ocaml opam # Fedora
sudo yum install code ocaml opam # CentOS
sudo apt install code ocaml opam # Debian & Ubuntu

# extension vscode
code --install-extension jaredly.reason-vscode
```

Si vous êtes en version 4.09 vous devez passer à la version 4.08 car le plugin vscode (ne supporte pas cette version pour l'instant)
```
# changement de version
opam switch create 4.08.0
opam switch 4.08.0


# packages ocaml
opam install utop dune merlin ocp-indent ppx_inline_test
