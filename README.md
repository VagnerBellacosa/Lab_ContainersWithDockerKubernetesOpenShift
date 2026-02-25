# 🚀 Lab – Containers no IBM Z: Modernização Estratégica sem Abandonar o Core

## 🎯 Objetivo

Este laboratório demonstra como executar containers no ecossistema IBM Z utilizando Linux on Z (RHEL/SLES), OpenShift e integração com z/OS, explorando arquitetura híbrida de alta performance e baixa latência.

Aqui não estamos “levando o mainframe para a cloud”.

Estamos trazendo a cloud para dentro do mainframe.

---

## 🧠 Conceito Central

Mainframe não é legado.

É o núcleo transacional mais estável da indústria.

Containers não substituem o core.
Eles orbitam o core.

Este laboratório explora:

- Linux on Z rodando em IFL
- Deploy de containers via OpenShift
- Exposição de APIs
- Integração com serviços no z/OS
- Avaliação de latência e arquitetura

---

## 🏗️ Arquitetura do Lab

Ambiente lógico:

- LPAR 1 – z/OS (Core transacional)
- LPAR 2 – Linux on Z (RHEL ou SLES)
- IFL dedicado para workloads Linux
- Cluster OpenShift executando containers
- API Gateway interno
- Comunicação via REST/MQ

Fluxo:

Client → OpenShift → Microserviço (Container)
 → API → z/OS Service → Resposta



Sem hops externos.
Sem latência de internet.
Sem exposição desnecessária.

---

## 🔧 Tecnologias Envolvidas

- IBM Z (z17 ou equivalente)
- Linux on Z (s390x)
- IFL (Integrated Facility for Linux)
- Docker / Podman
- Kubernetes
- OpenShift
- z/OS
- APIs REST
- Mensageria (MQ opcional)

---

## 💡 O Que Este Lab Demonstra

✔ Consolidação de workloads Linux dentro do Z  
✔ Escala vertical vs escala horizontal  
✔ Proximidade arquitetural entre microserviços e core  
✔ Governança enterprise com OpenShift  
✔ Modernização progressiva, não disruptiva  

---

## 🔥 Perguntas Estratégicas que Este Lab Responde

- Por que rodar microsserviço crítico longe do core?
- Container reduz custo ou apenas muda o modelo?
- Latência interna compensa frente à cloud pública?
- É possível modernizar sem migrar?

---

## 📊 Resultados Esperados

Ao final deste laboratório você será capaz de:

- Provisionar ambiente Linux on Z
- Criar e subir um container
- Orquestrar via OpenShift
- Integrar com um serviço no z/OS
- Avaliar impacto de arquitetura híbrida
- Discutir custo, latência e segurança em nível executivo

---

## 🧭 Mentalidade Necessária

Este não é um lab para aprender Docker.

É um lab para entender:

> Arquitetura híbrida consciente.

O profissional que domina:

- z/OS
- Linux on Z
- Containers
- APIs
- Segurança corporativa

Não é apenas técnico.

É arquiteto de transição.

---

## ⚠️ Erros Comuns

❌ Achar que container substitui mainframe  
❌ Ignorar custo de workload mal desenhado  
❌ Desconsiderar latência de rede  
❌ Modernizar sem estratégia  

---

## 🏁 Conclusão

O IBM Z não está competindo com a cloud.

Ele está absorvendo o que faz sentido da cloud.

Este laboratório mostra que:

- Modernização não exige migração
- Containers são extensão estratégica
- Mainframe continua sendo o núcleo

---

## ☕ Bellacosa Insight

O futuro não é:

Mainframe **ou** Cloud.

O futuro é:

Mainframe **e** Cloud, com inteligência arquitetural.
