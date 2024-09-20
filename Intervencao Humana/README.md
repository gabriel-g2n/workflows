# Funcionalidade de Bloqueio do Agente de IA no WhatsApp Web com N8N, Redis e Evolution API

Este repositório contém os arquivos de um fluxo do **n8n** desenvolvido no vídeo [Como Criar Funcionalidade de Bloqueio do Agente de IA no WhatsApp Web com N8N, Redis e Evolution API](LINK_DO_VIDEO). O vídeo ensina como automatizar o bloqueio temporário de um agente de IA no WhatsApp Web sempre que um humano intervém em uma conversa, garantindo uma interação mais eficiente entre humano e máquina.

## Descrição

No vídeo, você aprenderá a resolver um problema comum em sistemas de atendimento automatizado: o agente de IA continua respondendo após a intervenção de um humano, gerando confusão para o usuário. A solução apresentada utiliza o **n8n**, **Redis** (para armazenar o estado de bloqueio temporário) e a **Evolution API** (para integrar o WhatsApp Web), permitindo bloquear temporariamente o agente de IA com base no tempo da última mensagem humana.

Este repositório contém os arquivos necessários para replicar essa solução no **n8n**.

## O que você vai aprender

- **Integração WhatsApp Web + n8n utilizando Evolution API**: Como configurar e conectar o WhatsApp Web ao **n8n**.
- **Configuração do bloqueio do agente de IA**: Lógica para bloquear o agente após a intervenção humana, controlada pelo tempo da última mensagem do usuário.
- **Uso do Redis para armazenar estados temporários**: Como usar o **Redis** para armazenar o status de bloqueio do agente, sem a necessidade de um banco de dados completo ou de outras ferramentas como Chatwoot.
- **Evitar o uso de bancos de dados complexos**: Implementação leve e eficiente sem a necessidade de sistemas adicionais.

## Como usar este repositório

1. **Baixar o json**
   
   Baixe o Json do fluxo escolhido e importe no N8N.