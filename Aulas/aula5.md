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

## 📚 Referências

- Tanenbaum – Sistemas Operacionais Modernos  
- Silberschatz – Fundamentos de Sistemas Operacionais  
- Stallings – Sistemas Operacionais  
- Documentações oficiais (Red Hat, Docker)
