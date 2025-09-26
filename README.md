# Nexus-CLI

# Instalando WSL

Instale o WSL (Ubuntu) via Microsoft Store
execute siga os passos e escolha um username e uma senha.

# Atualizando e instalando dependencias
```
sudo apt update & sudo apt upgrade -y
sudo apt install screen curl build-essential pkg-config libssl-dev git-all -y
sudo apt install protobuf-compiler -y
sudo apt update
```
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
```
source $HOME/.cargo/env
```
```
rustup target add riscv32i-unknown-none-elf
```

# Atualizando e instalando dependencias

```
screen -S nexus
```

Se der erro no codigo acima execute o codigo abaixo

```
sudo apt install screen -y
```

# Iniciando tela 
````
screen -S nexus
````

# Instalando CLI

````
curl https://cli.nexus.xyz/ | sh
````

Mude onde está your-node-id pelo ID do node pego no https://app.nexus.xyz/nodes
````
source ~/.bashrc

nexus-network start --node-id your-node-id
````


