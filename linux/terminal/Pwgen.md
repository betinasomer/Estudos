# Pwgen

Gerador de senhas fortes via terminal

### Instalação

Ubuntu e derivados:

```
sudo apt install pwgen
```

### Execução

Geração de senha com números, letras maiúsculas e minúsculas

```sh
# Comando
pwgen -s -1 <numero de digitos>

# Exemplo
pwgen -s -1 8
```

Geração de senha com caracteres especiais, números, letras maiúsculas e minúsculas

```sh
# Comando
pwgen -s -1 -y <numero de digitos> 

# Exemplo
pwgen -s -1 -y 8
```
