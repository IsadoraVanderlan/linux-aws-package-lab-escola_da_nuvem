# 🚀 Infraestrutura RHEL e Gerenciamento AWS Cloud - LAB Escola da Nuvem

Este laboratório prático demonstra competências em administração de sistemas **Linux (Red Hat)** e integração com serviços de nuvem da **AWS**. O projeto foca em governança de pacotes, segurança do sistema operacional e automação via CLI.

### 🎬 Arquitetura do Lab (Diagrama Animado)
![Arquitetura do Lab](./diagrama%20animado.gif)

---

## 📝 Visão Geral do Projeto
O objetivo deste lab foi configurar um ambiente seguro em Red Hat Enterprise Linux, realizar a manutenção preventiva do sistema e estabelecer uma conexão autenticada com a infraestrutura AWS para gerenciamento programático de recursos.

### 🛠️ Tecnologias e Ferramentas Utilizadas:
*   **SO:** Red Hat Enterprise Linux (RHEL)
*   **Gerenciamento de Pacotes:** `YUM` (Yellowdog Updater, Modified)
*   **Cloud:** Amazon Web Services (AWS)
*   **Interface:** AWS CLI v2 e Terminal Bash
*   **Serviços:** EC2 (Elastic Compute Cloud)

---

## 🎯 Principais Competências Demonstradas

### 1. Governança e Segurança do SO
*   **Patch Management:** Implementação de atualizações críticas com foco exclusivo em segurança (`--security`).
*   **Lifecycle de Pacotes:** Instalação e configuração do servidor web Apache (`httpd`) para validação de serviços.

### 2. Gestão de Mudanças e Resiliência (Rollback)
*   **Auditoria de Transações:** Uso do `yum history` para rastrear modificações no sistema.
*   **Rollback Estratégico:** Capacidade de reverter estados do sistema através do comando `undo`, garantindo a restauração de dependências e estabilidade operacional.

### 3. Integração e Autenticação Cloud (AWS)
*   **Deployment de Ferramentas:** Instalação manual da **AWS CLI v2** a partir de pacotes oficiais.
*   **Segurança Programática:** Configuração de perfis de acesso, gestão de chaves (`Access Keys`) e tokens de sessão via arquivos de configuração ocultos.
*   **Interação com API AWS:** Validação de conectividade e consulta de atributos de instâncias EC2 diretamente pelo terminal Linux.

---

## 📁 Estrutura do Laboratório

### 🔹 Etapa 1: Manutenção do Sistema
Focada em auditoria de diretórios, atualização de segurança do kernel e pacotes, e deploy de serviços básicos.

### 🔹 Etapa 2: Auditoria e Rollback
Demonstração de como recuperar o sistema após instalações indesejadas, utilizando o histórico de transações para auditoria técnica.

### 🔹 Etapa 3: CLI e Conectividade Cloud
Instalação da stack AWS, configuração de variáveis de ambiente e teste de leitura de metadados de instâncias EC2 em ambiente de produção.

---

## 🚀 Como Executar este Lab
Os comandos detalhados e as etapas técnicas podem ser consultados no histórico de commits deste repositório ou executados seguindo o roteiro oficial de administração de sistemas Linux.

---
*Este projeto faz parte do meu portfólio técnico de Cloud e SysAdmin.*
