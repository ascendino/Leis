---
tags:
  - informatica
  - redes
projeto: PRF
data_criacao: 2026-05-19
---
# Intranet

## 📌 1. Conceito Central
Uma rede de computadores **corporativa, privada, restrita e exclusiva** a um público específico de uma organização (ex: servidores da PRF). 
* **Objetivo:** Compartilhar informações, centralizar documentos, acelerar processos internos e melhorar a comunicação organizacional.

---

## 🛠️ 2. Tecnologias e Infraestrutura (Regra de Ouro)
* **Mesmas Tecnologias:** A Intranet utiliza **exatamente os mesmos** protocolos, padrões, serviços e softwares comuns à [[Internet]] (como a pilha [[TCP-IP]], servidores Web, navegadores, e-mail, etc.).
	* *Tudo o que foi desenvolvido para a Internet pode ser replicado dentro de uma Intranet.*
* **Independência da Internet (Cai Muito!):** A Intranet **NÃO depende da Internet para funcionar**. 
	* Ela pode existir de forma totalmente isolada do mundo exterior, operando estritamente dentro de uma rede local (LAN).
	* **Cenário Comum:** Na prática, a maioria está conectada à Internet para permitir que colaboradores em locais ou cidades diferentes se comuniquem, mas essa conexão externa **não é um requisito obrigatório** para a existência da Intranet.

---

## ⚖️ 3. O Divisor de Águas: Internet vs. Intranet
A diferença crucial entre as duas redes **NÃO é a tecnologia**, mas sim o **escopo de acesso**:

| Característica | [[Internet]] | Intranet |
| :--- | :--- | :--- |
| **Perfil do Acesso** | **Pública** (Qualquer um pode acessar). | **Privada** (Restrita a membros autorizados). |
| **Foco** | Comunicação e serviços globais. | Integração e produtividade interna. |

---

## ⚠️ 4. Pegadinhas do Cebraspe para Ficar Alerta (Gatilhos de Erro)

> ❌ **Pegadinha 1: "Por utilizar os mesmos protocolos da Internet, uma Intranet está necessariamente exposta aos mesmos ataques vindos da rede pública."**
> * **Realidade:** **ERRADO.** Se a Intranet estiver isolada ou protegida por um [[Firewall]] rígido e [[VPN]], o acesso externo é bloqueado.

> ❌ **Pegadinha 2: "Uma Intranet só pode ser acessada por computadores que estejam localizados fisicamente dentro do prédio da empresa."**
> * **Realidade:** **ERRADO.** É possível acessar a Intranet de forma remota (ex: em Home Office) através da Internet, utilizando uma conexão segura via [[VPN]] (o que estende o conceito para uma [[Extranet]]).

---

## 🔗 Conexões Relacionadas (Links do Obsidian)
* [[Internet]]
* [[Extranet]]
* [[TCP-IP]]
* [[VPN]] -> Ferramenta que permite o acesso remoto seguro à Intranet.
* [[Firewall]]