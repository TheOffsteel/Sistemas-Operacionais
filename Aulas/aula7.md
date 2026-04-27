# 📘 Aula 07 — Nuvem e Sistemas Operacionais

## ☁️ 1. Conceito de Computação em Nuvem

A computação em nuvem permite acessar recursos computacionais (servidores, armazenamento e aplicações) pela internet **sob demanda**, sem a necessidade de possuir infraestrutura própria.

### Principais características (modelo NIST):

* **Autoatendimento sob demanda**: provisionamento automático de recursos
* **Acesso amplo à rede**: acesso via diferentes dispositivos
* **Pool de recursos**: compartilhamento entre múltiplos usuários
* **Elasticidade**: escalabilidade rápida conforme a demanda
* **Serviço mensurável**: cobrança baseada no uso (pay-per-use)

➡️ Transição de **CAPEX (investimento em hardware)** para **OPEX (pagamento por uso)**.

---

## 🖥️ 2. Papel do Sistema Operacional na Nuvem

O Sistema Operacional (SO) é responsável por:

* Abstrair o hardware
* Gerenciar CPU, memória e processos

### Virtualização (base da cloud)

* Permite múltiplas **máquinas virtuais (VMs)** em um único servidor
* Utiliza **hypervisor (VMM)**
* Garante isolamento e melhor aproveitamento dos recursos

---

## ⚙️ 3. Recursos e Alta Disponibilidade

### Recursos sob demanda:

* Provisionamento automático
* Escalabilidade e elasticidade

### Alta disponibilidade:

* **Zonas de disponibilidade** (datacenters separados)
* **Balanceamento de carga**
* **Replicação de dados**
* **Failover automático**

---

## 🧩 4. Modelos de Serviço

### IaaS (Infrastructure as a Service)

* Cliente gerencia SO e aplicações
* Maior controle e flexibilidade
* Exemplo: AWS EC2

### PaaS (Platform as a Service)

* Provedor gerencia infraestrutura e plataforma
* Desenvolvedor foca no código
* Exemplo: Heroku

### SaaS (Software as a Service)

* Software pronto via internet
* Usuário não gerencia nada
* Exemplo: Google Workspace

---

## 🌐 5. Modelos de Implantação

* **Nuvem Pública**: compartilhada, menor custo
* **Nuvem Privada**: dedicada, maior controle
* **Nuvem Híbrida**: combinação entre pública e privada

---

## 🏢 6. Provedores de Cloud

* AWS (Amazon Web Services)
* Microsoft Azure
* Google Cloud Platform (GCP)

---

## ⚖️ 7. Vantagens e Desafios

### ✅ Vantagens:

* Redução de custos (CAPEX → OPEX)
* Escalabilidade sob demanda
* Alta disponibilidade
* Acesso global
* Inovação acelerada

### ⚠️ Desafios:

* Vendor lock-in
* Segurança e conformidade (LGPD)
* Custos imprevisíveis
* Latência de rede
* Complexidade (multicloud/híbrido)

---

## 🔐 8. Segurança na Nuvem

Modelo de **responsabilidade compartilhada**:

* **Provedor**: segurança da infraestrutura
* **Cliente**: segurança dos dados e acessos

Inclui:

* Criptografia de dados
* Controle de acesso
* Monitoramento contínuo

---

## 📦 9. Containers e Microsserviços

### Containers:

* Empacotam aplicação + dependências
* Leves e portáteis
* Exemplo: Docker

### Microsserviços:

* Aplicações divididas em serviços independentes
* Comunicação via API
* Maior escalabilidade e resiliência

---

## 🔙 10. Backend e Web Services

* **Backend**: processa dados e regras de negócio
* **Web Services**: comunicação entre sistemas via HTTP/HTTPS
* **APIs**: integração entre diferentes sistemas

---

## 🚀 11. API REST com Express + Deploy

### Desenvolvimento:

* Node.js + Express
* Uso de CORS
* Execução com `node index.js`

### Deploy:

* Repositório no GitHub
* Plataforma Render:

  * Deploy automático
  * SSL gratuito
  * Escalabilidade

---

## 🧪 12. Atividade Prática

1. Criar aplicação com Express exibindo informações do SO:

   * Hostname
   * Plataforma
   * CPU
   * Memória
   * Tempo de atividade

2. Subir projeto no GitHub

3. Fazer deploy no Render

4. Comparar execução:

   * Local vs Nuvem

5. Relacionar com conceitos de SO:

   * Processos
   * Memória
   * CPU
   * Virtualização

6. Documentar todo o processo:

   * Instalação
   * Desenvolvimento
   * Deploy
   * Testes
   * Conclusões

---

## 🧠 Conclusão

A computação em nuvem está diretamente ligada aos conceitos de Sistemas Operacionais, especialmente:

* Gerenciamento de recursos
* Virtualização
* Processos e memória

Ela possibilita **alta escalabilidade, flexibilidade e redução de custos**, sendo essencial para sistemas modernos.

---