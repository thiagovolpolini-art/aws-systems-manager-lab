# aws-systems-manager-lab
# AWS Systems Manager Lab

Laboratório prático realizado com foco no uso do AWS Systems Manager para gerenciamento de instâncias EC2.

## Objetivo

Explorar recursos do AWS Systems Manager para administrar uma instância EC2 sem depender de acesso SSH tradicional.

## Serviços e recursos utilizados

- AWS Systems Manager
- Fleet Manager
- Inventory
- Run Command
- Parameter Store
- Session Manager
- Amazon EC2
- AWS CLI

## Atividades realizadas

### 1. Inventory

Configurei o inventário do Systems Manager para coletar informações da instância gerenciada, como:

- Aplicações instaladas
- Sistema operacional
- Configurações da instância
- Componentes do ambiente

### 2. Run Command

Utilizei o Run Command para instalar remotamente uma aplicação web na instância EC2.

A instalação incluiu componentes como:

- Apache HTTP Server
- PHP
- AWS SDK for PHP
- Aplicação Widget Manufacturing

Tudo foi realizado sem conexão SSH.

### 3. Parameter Store

Criei o parâmetro:

text
dashboard/show-beta-features

## Resultado

Ao final do laboratório, consegui instalar e gerenciar uma aplicação web utilizando os recursos do AWS Systems Manager.

![AWS Systems Manager Lab](aws-systems-manager-lab.png.png)
