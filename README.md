# 🤖 RoBoiTuva: Guia de Iniciação à Robótica EV3

O projeto visa viabilizar o ensino de robótica e programação tanto para os alunos do **IFSP Campus de Boituva** quanto para os membros interessados da comunidade, focando na plataforma **LEGO EV3** utilizando **MicroPython**.

---

## 🧭 Visão Geral e Sumário

Neste guia você encontrará um passo a passo detalhado para configurar o ambiente de desenvolvimento. Iremos instalar os softwares que utilizaremos durante os encontros presenciais e tutoriais disponíveis em nosso canal oficial.

### 📝 Conteúdo

* [Pré-requisitos](#-pr%C3%A9-requisitos)
* [Instalação do Firmware (Micro SD)](#-instala%C3%A7%C3%A3o-do-firmware-micro-sd)
* [Pós-instalação (Configuração do VSCode)](#-p%C3%B3s-instala%C3%A7%C3%A3o-configura%C3%A7%C3%A3o-do-vscode)
* [Autores](#-autores)
* [Licença](#-licen%C3%A7a)

---

## ⬇️ Pré-requisitos

Realize o download das seguintes ferramentas e arquivos essenciais:

| Ferramenta | Descrição | Download |
| :--- | :--- | :---: |
| **Visual Studio Code (VSCode)** | Editor de código-fonte. | [![Download VSCode](https://img.shields.io/badge/Download-VSCode-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)](https://code.visualstudio.com/download) |
| **Balena Etcher** | Utilitário para gravação de imagens em mídias USB/SD. | [![Download Etcher](https://img.shields.io/badge/Download-Etcher-007ACC?style=for-the-badge&logo=etcher&logoColor=white)](https://etcher.balena.io/#download-etcher) |
| **EV3 MicroPython Firmware** | Imagem oficial para Micro SD que permite o uso de MicroPython no bloco EV3. | [![Download Firmware](https://img.shields.io/badge/Download-Firmware-F77800?style=for-the-badge&logo=lego&logoColor=black)](https://education.lego.com/en-us/product-resources/mindstorms-ev3/teacher-resources/python-for-ev3/) |

---

## 💿 Instalação do Firmware (Micro SD)

### Passo 1: Instalação Inicial dos Softwares

1.  Instale o **Visual Studio Code** e o **Balena Etcher** em seu computador.
   
### Passo 2: Gravação da Imagem no Micro SD

1.  **Extraia o arquivo zip** do firmware que foi baixado. Você terá um arquivo com a extensão `.iso`.
2.  Plugue o Micro SD ao computador usando um adaptador.
3.  Abra o **Balena Etcher**:
    * Clique em *Flash from file* e selecione o arquivo `.iso` que você acabou de extrair.
    * Clique em *Select target* e escolha o seu cartão Micro SD.
    * Clique em *Flash* e aguarde a conclusão da instalação.
4.  Após a conclusão, remova o Micro SD do computador e insira-o no bloco **EV3**.

### Passo 3: Inicialização do EV3

1.  Ligue o bloco EV3.
2.  Aguarde a inicialização do sistema operacional. Durante o processo de *boot*, os LEDs do bloco piscarão em laranja e haverá bastante texto no visor — **isso é normal**.

---

## 💻 Pós-instalação (Configuração do VSCode)

Após a instalação do firmware, o próximo passo é configurar o ambiente de desenvolvimento no VSCode para comunicação com o EV3:

1.  Instale a extensão oficial **LEGO® MINDSTORMS® EV3 MicroPython** no VSCode.
    * [Link direto para a Extensão](https://marketplace.visualstudio.com/items?itemName=lego-education.ev3-micropython)

2.  Com a extensão instalada e o EV3 ligado, conecte-o ao computador através de um **cabo USB**.
3.  O dispositivo será reconhecido no computador e, consequentemente, no VSCode. A partir desse momento, você poderá iniciar o desenvolvimento dos programas em **MicroPython**.

---

## 👥 Autores

| Nome | Função | Links |
| :--- | :--- | :--- |
| **Marcelo Frate** | Professor Doutor | [Lattes](http://lattes.cnpq.br/8632724748282199) |
| **Emerson J.** | Monitor de Robótica e Programador | [LinkedIn](https://www.linkedin.com/in/%C3%A9merson-j%C3%BAnior-a3b216214/) |
| **Mateus de Melo** | Programador | [LinkedIn](https://www.linkedin.com/in/mateusdemelo/) |

---

## 🛡️ Licença

Este projeto está licenciado sob a Licença MIT.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://mit-license.org/)

## 🙏 Agradecimentos

Agradecemos a todos os participantes do projeto e a todos aqueles que foram beneficiados de alguma forma com os trabalhos que desenvolvemos.

---
