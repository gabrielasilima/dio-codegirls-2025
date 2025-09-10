# dio-codegirls-2025
Desafio DIO - Gerenciamento de Instâncias EC2 na AWS

Este repositório documenta a prática (simulada) do laboratório sobre EC2 na AWS, proposta pela DIO. 
O objetivo foi **consolidar os conhecimentos em gerenciamento de instâncias EC2**. 

## Objetivos de Aprendizagem
- Compreender o processo de criação de uma instância EC2
- Documentar os principais comandos e configurações
- Explorar boas práticas de snapshots, grupos de segurança e encerramento de instâncias
- Utilizar o GitHub para compartilhar documentação técnica

## Passo a Passo 

### 1. Criação da Instância
- Nome: dio-ec2-lab
- Tipo: t2.micro (gratuita no Free Tier)
- Par de chaves: criado e baixado (.pem)
- Grupo de Segurança:
  - Porta **22** liberada (SSH)
  - Porta **80** liberada (HTTP)

### 2. Conexão via SSH
No terminal:
bash
ssh -i "minha-chave.pem" ec2-user@<IP_DA_INSTANCIA>
