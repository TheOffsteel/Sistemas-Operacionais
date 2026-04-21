# Aula 03 - Conceitos, Funções e Tipos de Sistemas Operacionais

## 📌 Introdução aos Sistemas Operacionais
Sistema Operacional (SO) é o software responsável por gerenciar o hardware e fornecer serviços para programas.

- Atua como intermediário entre usuário e hardware
- Gerencia recursos: CPU, memória, disco e dispositivos

---

## 🖥️ Tipos de Sistemas Operacionais

### 🏢 Sistemas de Grande Porte (Mainframes)
- Alto desempenho e processamento massivo
- Suporte a muitos usuários simultâneos
- Uso: bancos, e-commerce, grandes empresas

**Características:**
- Alta confiabilidade
- Processamento em lote e transações (TPS)
- Segurança elevada

---

### 🌐 Sistemas Operacionais de Servidor
- Atendem múltiplos usuários via rede
- Serviços: web, arquivos, banco de dados

**Exemplos:**
- Linux
- Windows Server

**Foco:** estabilidade, escalabilidade e compartilhamento

---

### ⚙️ Sistemas Multiprocessadores
- Utilizam múltiplas CPUs ou núcleos
- Execução paralela

**Desafios:**
- Escalonamento de processos
- Sincronização (locks, semáforos)
- Coerência de cache

---

### 💻 Sistemas de Computadores Pessoais
- Uso individual
- Interface gráfica
- Suporte a múltiplos programas

**Exemplos:**
- Windows
- macOS
- Linux

---

### 📱 Sistemas Operacionais Portáteis (Mobile)
- Foco em dispositivos móveis

**Características:**
- Gerenciamento de energia
- Suporte a sensores (GPS, câmera)
- Segurança por permissões

**Exemplos:**
- Android
- iOS

---

### 🔌 Sistemas Embarcados
- Dispositivos dedicados com poucos recursos

**Exemplos:**
- Micro-ondas
- Smart TVs
- Sistemas automotivos

**Características:**
- Baixo consumo
- Software em ROM/flash
- Pouca interação do usuário

---

### 📡 Sistemas de Nós Sensores
- Dispositivos pequenos e com bateria limitada

**Uso:**
- Monitoramento ambiental
- Agricultura
- Aplicações militares

---

### ⏱️ Sistemas de Tempo Real

- **Hard Real-Time:** falhas são críticas (ex: aviões)
- **Soft Real-Time:** atrasos são toleráveis (ex: streaming)

---

### 💳 Sistemas de Cartões Inteligentes
- Recursos limitados
- Alta segurança (criptografia)
- Execução de pequenos programas (applets)

---

## 🔧 Introdução ao Git

### O que é?
- Sistema de controle de versão

### Funções:
- Armazenar histórico de alterações
- Permitir retorno a versões anteriores
- Sincronizar com repositórios online (GitHub)

---

## ⚙️ Uso do Git (Resumo)

### Instalação:
- Baixar em: git-scm.com
- Verificar com: `git --version`

### Configuração:
```bash
git config --global user.name "Nome"
git config --global user.email "Email"