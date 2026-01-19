# nmcli-wifi.sh

Script simples para gerenciar Wi‑Fi utilizando o **nmcli** (NetworkManager).

Ideal para ambientes sem interface gráfica, *tiling window managers* e setups minimalistas.


## Requisitos

* (nmcli) NetworkManager



## Uso

Dê permissão de execução ao script:

```bash
chmod +x nmcli-wifi.sh
```

Execute:

```bash
./nmcli-wifi
```

O script irá:

* Mostrar as redes Wi‑Fi disponíveis
* Indicar a rede atualmente conectada (se houver)
* Permitir conectar a uma rede
* Pedir senha apenas quando necessário
* Permitir ativar/desativar o Wi‑Fi
* Permitir desconectar da rede atual

Tudo de forma interativa no terminal.
