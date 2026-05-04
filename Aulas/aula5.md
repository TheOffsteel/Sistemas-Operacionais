# Aula 05 - Introdução à Virtualização

## 📌 Definição de Virtualização
Virtualização é uma tecnologia que permite executar múltiplos sistemas operacionais em um único computador físico.

- Cria ambientes isolados (máquinas virtuais)
- Simula hardware real
- Permite testes sem afetar o sistema principal
- Muito usada em desenvolvimento, testes e produção

---

## ✅ Vantagens da Virtualização

- **Economia de hardware:** consolidação de vários sistemas em uma única máquina
- **Ambientes isolados:** maior segurança para testes
- **Facilidade para testes:** snapshots e recuperação rápida
- **Execução de múltiplos SOs:** Windows, Linux, macOS, etc.

---

## 💻 Conceito de Máquina Virtual

- **Host (Hospedeiro):** sistema operacional principal
- **Virtualização:** camada que simula o hardware
- **Guest (Convidado):** sistema operacional dentro da VM

---

## 🧰 Oracle VirtualBox

- Ferramenta de virtualização da Oracle
- Gratuita e open-source (uso pessoal/educacional)
- Multiplataforma (Windows, Linux, macOS, Solaris)
- Muito usada em ambientes educacionais

### Interface
- **Painel principal:** lista de VMs
- **Configurações:** CPU, RAM, disco, dispositivos
- **Armazenamento:** discos virtuais e ISOs
- **Rede:** configuração de conectividade

---

## 🖥️ Criando uma Máquina Virtual

1. Clique em **"Novo"**
2. Escolha o **tipo de sistema operacional**
3. Defina a **memória RAM** (mínimo recomendado: 2048 MB)
4. Crie um **disco virtual (20–40 GB)**

---

## ⚙️ Instalando um Sistema Operacional

1. Baixar arquivo **.ISO**
2. Montar ISO no armazenamento da VM
3. Iniciar a VM
4. Seguir instalação do sistema

---

## 🐧 Exemplo: Tiny Core Linux

- Distribuição Linux extremamente leve
- ISO entre 17 MB e 248 MB
- Ideal para testes e virtualização
- Sistema modular e rápido

---

## 📝 Atividade

1. Instalar o VirtualBox  
2. Criar uma máquina virtual  
3. Instalar um Linux leve (Tiny Core, Lubuntu ou Xubuntu)  
4. Testar o sistema  
5. Documentar o processo em um manual e enviar ao repositório

---

# 📘 Manual de Virtualização — Windows 95 no VirtualBox

## 🧠 Objetivo

Demonstrar, na prática, o uso de virtualização por meio da criação de uma máquina virtual rodando o sistema operacional **Windows 95**, analisando seu funcionamento e relacionando com conceitos de Sistemas Operacionais.

---

## 🛠️ 1. Instalação do Ambiente

Para a realização da atividade, foram utilizadas as seguintes ferramentas:

* **Oracle VirtualBox**: software de virtualização
* **Arquivo ISO do Windows 95**
* **Sistema operacional hospedeiro (Host)**: Windows 10/11

O VirtualBox foi escolhido por ser gratuito, multiplataforma e amplamente utilizado em ambientes educacionais.

---

## 💻 2. Criação da Máquina Virtual

A máquina virtual foi criada seguindo os passos:

1. Abrir o VirtualBox e clicar em **"Nova"**
2. Definir:

   * Nome: `Windows95-VM`
   * Tipo: Microsoft Windows
   * Versão: Windows 95
3. Configurar memória RAM:

   * 64 MB (suficiente para o sistema)
4. Criar disco virtual:

   * Tipo: VDI
   * Alocação dinâmica
   * Tamanho: 2 GB

---

## 📀 3. Instalação do Windows 95

O processo de instalação ocorreu da seguinte forma:

1. Montagem da ISO do Windows 95 no armazenamento da VM
2. Inicialização da máquina virtual
3. Execução do instalador do sistema
4. Configuração básica (idioma, nome do computador, etc.)
5. Finalização da instalação e inicialização do sistema

Após a instalação, o sistema foi iniciado com sucesso, exibindo a interface clássica do Windows 95.

---

## 🔍 4. Testes Realizados

Durante a execução da máquina virtual, foram realizados testes básicos:

* Inicialização do sistema
* Navegação pela interface gráfica
* Acesso ao sistema de arquivos
* Execução de aplicativos simples (ex: Bloco de Notas)

O sistema apresentou funcionamento estável dentro das limitações esperadas.

---

## ⚙️ 5. Análise Técnica (Conceitos de SO)

### 🔹 Virtualização

A máquina virtual simula um computador completo dentro do sistema hospedeiro, permitindo executar um sistema operacional antigo sem afetar o sistema principal.

### 🔹 Sistema Hospedeiro (Host) vs Convidado (Guest)

* **Host**: sistema real (Windows 10/11)
* **Guest**: Windows 95 rodando na VM

Essa separação garante isolamento entre os ambientes.

### 🔹 Gerenciamento de Recursos

O VirtualBox controla a alocação de:

* Memória RAM
* CPU
* Armazenamento

O Windows 95 utiliza apenas os recursos definidos, não tendo acesso direto ao hardware físico.

### 🔹 Processos

Dentro da VM, o Windows 95 executa seus próprios processos de forma independente, enquanto o VirtualBox é um processo do sistema hospedeiro.

### 🔹 Limitações do Sistema

Por ser um sistema antigo:

* Não possui suporte moderno a hardware
* Tem limitações de memória e processamento
* Interface e funcionalidades são básicas

---

## 📊 6. Vantagens da Virtualização Observadas

* Execução de sistemas antigos sem necessidade de hardware específico
* Isolamento total do ambiente
* Facilidade para testes e aprendizado
* Baixo risco para o sistema principal

---

## ⚠️ 7. Desafios Encontrados

* Compatibilidade com sistemas antigos
* Necessidade de configurações específicas (baixa RAM e disco)
* Limitações de drivers e resolução gráfica

---


## 📊 Slides do Projeto

Os slides estão disponíveis no arquivo:

- [ApresentacaoWin95.pdf](../Assets/ApresentaçãoSO.pdf)

## 🧾 8. Conclusão

A virtualização permite executar múltiplos sistemas operacionais em um único hardware físico, de forma isolada e segura.

A utilização do Windows 95 evidenciou:

* A evolução dos sistemas operacionais
* A importância do gerenciamento de recursos
* O papel da virtualização na abstração de hardware

Essa prática reforça como a virtualização é essencial tanto para testes quanto para ambientes modernos de computação, incluindo a computação em nuvem.

---

## 📚 Referências

- Tanenbaum – Sistemas Operacionais Modernos  
- Silberschatz – Fundamentos de Sistemas Operacionais  
- Stallings – Sistemas Operacionais  
- Documentações oficiais (Red Hat, Docker)
