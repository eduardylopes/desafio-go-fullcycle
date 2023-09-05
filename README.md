# Desafio Full Cycle: Imagem em Go (2MB)

Este repositório foi criado como parte do Desafio Full Cycle, que tem como objetivo criar uma imagem em Go que não ultrapasse o tamanho máximo de 2MB.

## Descrição do Desafio

O desafio consiste em criar uma aplicação simples em Go que seja empacotada em uma imagem Docker e que essa imagem não exceda 2MB de tamanho. Isso envolve otimizar a imagem e o código para atingir esse objetivo.

## Tecnologias Utilizadas

- [Go](https://golang.org/): A linguagem de programação utilizada para criar a aplicação.
- [Docker](https://www.docker.com/): A ferramenta de containerização para empacotar a aplicação em uma imagem.

## Instruções de Uso

1. Certifique-se de ter o Docker instalado em sua máquina.
2. Clone este repositório:

   ```bash
   git clone https://github.com/eduardylopes/desafio-go-fullcycle
   ```

3. Faça um build da imagem docker:
   ```bash
   docker build -t <nome-da-imagem> .
   ```
4. Execute o container baseado na imagem docker criada:
   ```bash
   docker run --rm <nome-da-imagem>
   ```

### Docker Hub

- [Repositório da imagem](https://hub.docker.com/repository/docker/eduardylopes/desafio-go-fullcycle/general)
