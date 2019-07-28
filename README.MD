
```console
# base
sudo pacman -S code ocaml opam #Arch Linux
sudo dnf install code ocaml opam # Fedora
sudo yum install code ocaml opam # CentOS
sudo apt install code ocaml opam # Debian & Ubuntu


# packages ocaml
opam install utop dune merlin easybird 

# extension vscode
code --install-extension freebroccolo.reasonml
code --install-extension hackwaly.ocaml-debugger
```



```json
{
  "version": "0.2.0",
  "configurations": [
    {
      "name": "OCaml Debug",
      "type": "ocaml-debugger",
      "request": "launch",
      "program": "${workspaceFolder}/a.out"
    }
  ]
}

```
