# Aula 06 - Estudo de Caso I

## 📌 Contexto

A **DevStore** é uma startup de desenvolvimento web que enfrenta problemas de:

- Falta de padronização dos servidores
- Baixa escalabilidade
- Dificuldade de organização da infraestrutura
- Riscos de segurança

Atualmente, utiliza servidores locais sem estrutura adequada, o que limita o crescimento da empresa.

---

## 🎯 Objetivo do Estudo de Caso

Propor uma **arquitetura de infraestrutura moderna**, utilizando:

- Sistemas Operacionais
- Virtualização
- Containerização
- Computação em Nuvem

---

## ⚠️ Problemas Identificados

- Desenvolvimento feito diretamente na máquina local
- Ausência de versionamento e testes
- Infraestrutura não escalável
- Falta de isolamento entre ambientes

---

## 🧰 Soluções Propostas

### 🖥️ Virtualização
- Criação de ambientes isolados
- Ideal para testes e segurança
- Maior consumo de recursos

---

### 📦 Containerização (Docker)
- Ambientes leves e rápidos
- Padronização de aplicações
- Portabilidade entre ambientes

**Vantagens:**
- Menor consumo de recursos
- Inicialização rápida
- Facilidade de deploy

---

### ☁️ Computação em Nuvem

Uso de provedores como AWS para:

- Escalabilidade sob demanda
- Alta disponibilidade
- Redução de custos com hardware físico

---

## 🔐 Segurança

Implementação de:

- Controle de acesso (usuários e permissões)
- Firewalls
- Monitoramento contínuo

Objetivo: garantir integridade e proteção dos dados

---

## 📊 Monitoramento

- Acompanhamento de:
  - CPU
  - Memória
  - Armazenamento

- Identificação de falhas e gargalos
- Melhoria da estabilidade do sistema

---

## 🌐 Planejamento de Infraestrutura

Deve incluir:

- Configuração de rede
- Armazenamento
- Controle de permissões
- Monitoramento

Além disso, justificar decisões com base em:

- Desempenho
- Custo
- Escalabilidade
- Segurança
- Compatibilidade

---

## 🔄 Integração de Conceitos

A solução deve integrar:

- Ambiente local
- Virtualização
- Containers
- Nuvem

Mostrando o papel do Sistema Operacional em cada camada

---

## 📝 Ponte para o Estudo de Caso

A partir dos conceitos apresentados, o próximo passo consiste no desenvolvimento do **planejamento completo da infraestrutura da DevStore**, aplicando:

- Arquitetura proposta  
- Escolhas tecnológicas (SO, Docker, Cloud, etc.)  
- Estratégias de implantação, segurança e escalabilidade  

---

# 📦 Estudo de Caso I - Sistemas Operacionais  
## DevStore - Planejamento de Infraestrutura

---

## 🧩 1. Introdução

A DevStore é uma startup de desenvolvimento web que enfrenta desafios relacionados à:

- Escalabilidade
- Organização da infraestrutura
- Segurança dos sistemas

Atualmente, a empresa utiliza servidores locais sem padronização e desenvolve aplicações diretamente nas máquinas dos desenvolvedores, sem versionamento ou testes automatizados.

---

## 🚨 2. Problemas Identificados

### 🔴 Infraestrutura
- Servidores locais não padronizados
- Dificuldade de gerenciamento
- Baixa escalabilidade

### 🔴 Desenvolvimento
- Ausência de versionamento (Git)
- Falta de testes automatizados
- Desenvolvimento direto no ambiente local

### 🔴 Operacional
- Ambientes não isolados
- Alto risco de falhas e inconsistências

---

## 🎯 3. Objetivos do Projeto

Propor uma arquitetura que seja:

- Escalável
- Segura
- Padronizada
- Reprodutível
- Otimizada em custo e desempenho

---

## 🏗️ 4. Arquitetura Proposta

### 🔹 4.1 Ambiente de Desenvolvimento

- Uso de **Docker**
- Uso de **Docker Compose**
- Versionamento com **Git**

**Benefícios:**
- Padronização do ambiente
- Facilidade de reprodução
- Redução de erros

---

### 🔹 4.2 Pipeline de Integração Contínua (CI/CD)

- Build automático
- Testes automatizados
- Deploy automatizado

**Fluxo:**
1. Desenvolvedor faz commit
2. Pipeline executa testes
3. Build da aplicação
4. Deploy automático

---

### 🔹 4.3 Virtualização

Uso de máquinas virtuais para:

- Ambientes de teste isolados
- Simulação de produção

**Vantagens:**
- Alto isolamento

**Desvantagens:**
- Alto consumo de recursos

---

### 🔹 4.4 Containerização

Uso de containers com Docker para:

- Execução das aplicações
- Padronização dos ambientes

**Vantagens:**
- Leveza
- Portabilidade
- Rápida inicialização

---

### 🔹 4.5 Computação em Nuvem

Hospedagem em nuvem (ex: AWS)

**Benefícios:**
- Escalabilidade sob demanda
- Alta disponibilidade
- Redução de custo com hardware

---

### 🔹 4.6 Ambientes Separados

- Desenvolvimento (Dev)
- Teste (Staging)
- Produção (Prod)

**Objetivo:**
Evitar falhas e garantir qualidade antes da entrega final

---

## 🔐 5. Segurança

- Controle de acesso (usuários e permissões)
- Uso de firewall
- Monitoramento contínuo
- Proteção de dados

---

## 📊 6. Monitoramento

Monitoramento de:

- CPU
- Memória
- Armazenamento
- Falhas do sistema

**Benefícios:**
- Identificação rápida de problemas
- Maior estabilidade

---

## 🌐 7. Configuração de Infraestrutura

### 🔹 Rede
- Configuração segura
- Isolamento entre ambientes

### 🔹 Armazenamento
- Uso de serviços gerenciados
- Backup automático

### 🔹 Permissões
- Controle baseado em papéis (RBAC)

---

## ⚖️ 8. Justificativas Técnicas

| Tecnologia | Justificativa |
|----------|--------------|
| Docker | Padronização e portabilidade |
| Virtualização | Isolamento completo |
| Nuvem | Escalabilidade e disponibilidade |
| CI/CD | Automação e redução de erros |
| Monitoramento | Controle e estabilidade |

---

## 🔄 9. Estratégia de Implantação

1. Migrar código para repositório Git
2. Containerizar aplicações com Docker
3. Implementar pipeline CI/CD
4. Configurar ambiente em nuvem
5. Implantar monitoramento
6. Aplicar políticas de segurança

---

## 🔧 10. Manutenção

- Atualizações periódicas
- Monitoramento contínuo
- Revisão de segurança
- Otimização de custos

---

## 📈 11. Estratégia de Expansão

- Escalar horizontalmente (mais instâncias)
- Uso de balanceadores de carga
- Adoção futura de orquestração (ex: Kubernetes)

---

## 🧠 12. Conclusão

A proposta transforma a DevStore de um ambiente:

❌ Desorganizado  
❌ Não escalável  
❌ Manual  

Para um ambiente:

✅ Automatizado  
✅ Escalável  
✅ Seguro  
✅ Padronizado  

---

## 📚 13. Referências

- Documentação Docker
- Documentação AWS
- Tanenbaum - Sistemas Operacionais Modernos
- Silberschatz - Fundamentos de Sistemas Operacionais

---