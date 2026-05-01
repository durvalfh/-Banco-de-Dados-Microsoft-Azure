# -Banco-de-Dados-Microsoft-Azure
 criar Instância Gerenciada de SQL
# 🚀 Desafio: Configuração de Banco de Dados no Azure

## 📌 Descrição

Este repositório documenta a realização de um laboratório prático com foco na criação e configuração de uma instância de banco de dados utilizando o Microsoft Azure.

O objetivo principal é consolidar conhecimentos sobre provisionamento de recursos em nuvem, utilizando o serviço Azure SQL Managed Instance.

---

## 🎯 Objetivos do Desafio

- Criar uma instância de banco de dados no Azure
- Compreender o processo de provisionamento de recursos
- Documentar o passo a passo da implementação
- Criar um material de apoio para estudos futuros

---

## ⚙️ Pré-requisitos

Para executar este laboratório, são necessários:

- Conta ativa no Microsoft Azure
- Permissões adequadas para criação de recursos
- Conhecimentos básicos em banco de dados e cloud

Segundo a documentação oficial, é necessário possuir uma assinatura ativa e permissões específicas para criação da instância. :contentReference[oaicite:2]{index=2}

---

## 🧪 Etapas Realizadas

### 1. Acesso ao Portal Azure
- Login no portal do Azure
- Navegação até o serviço Azure SQL

### 2. Criação da Instância

Durante a criação da instância, foram definidos:

- **Resource Group**
- **Nome da instância**
- **Região**
- **Método de autenticação (SQL Authentication)**

Esses são considerados os dados mínimos obrigatórios para provisionamento. :contentReference[oaicite:3]{index=3}

---

### 3. Configuração de Computação e Armazenamento

- Tier: General Purpose
- vCores: Definido conforme necessidade
- Armazenamento: Ajustado conforme volume esperado

A escolha desses parâmetros impacta diretamente no desempenho e custo da solução.

---

### 4. Configuração de Rede

- Criação de VNet e Subnet
- Definição de acesso (público ou privado)
- Configuração de segurança

A rede deve atender aos requisitos específicos do Azure SQL Managed Instance. :contentReference[oaicite:4]{index=4}

---

### 5. Revisão e Deploy

- Revisão das configurações
- Criação da instância
- Monitoramento do deployment

O processo de provisionamento pode levar alguns minutos ou mais, dependendo da configuração.

---

### 6. Criação do Banco de Dados

Após a instância:

- Criação de um banco de dados
- Configuração inicial
- Preparação para uso

---

## 📸 Capturas de Tela

As imagens do processo estão disponíveis na pasta `/images`:

- Criação da instância
- Configuração básica
- Configuração de rede
- Progresso do deploy

---

## 📚 Aprendizados

- Entendimento do fluxo de criação de recursos no Azure
- Importância da configuração de rede
- Impacto de escolhas de desempenho (vCores, storage)
- Organização de recursos com Resource Groups

---

## 💡 Dicas

- Sempre revisar configurações antes do deploy
- Utilizar boas práticas de nomenclatura
- Monitorar custos e uso de recursos
- Utilizar tags para organização

---

## 📎 Referência

Documentação oficial utilizada:

https://learn.microsoft.com/pt-br/azure/azure-sql/managed-instance/instance-create-quickstart

---

## 📌 Conclusão

Este laboratório permitiu consolidar conhecimentos essenciais sobre criação e gerenciamento de banco de dados na nuvem utilizando o Azure, além de reforçar a importância da documentação técnica como ferramenta de aprendizado e portfólio.