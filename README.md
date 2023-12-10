# desktop
Scripts ansible para configuração de máquina desktop

## Descrição

Esse repositório contém instruções ansible com as configurações para configurar uma máquina Debian 12 desktop para o meu padrão.

## Utilização

Para utilizar as configurações desse repositório, primeiro é necessário instalar
os seguintes pacotes:
  - `git`
  - `ansible`

No Debian 12:

```sh
sudo apt install git ansible
```

Depois, basta chamar `ansible-pull` a partir deste repositório:

```sh
sudo ansible-pull -U https://github.com/victoitor/desktop.git
```
