---
projeto: Concurso PRF 2026
foco: Engenharia de Alta Performance
meta_acertos: 80%
status: 🟢 EM FISCALIZAÇÃO INTERNA
---
# 🚓 Painel de Controle PRF: Central de Inteligência

> "O trânsito em condições seguras é um direito de todos e dever dos órgãos do SNT." (Art. 1º, §2º, CTB)

---
## 🎯 Métricas de Sprints & Controle de Voo
* **Ciclo Atual:** Rodada Inicial de Nivelamento (Junho/2026)
* **Regra de Ouro do Bloco (1:30h):** 60 min Teoria/Lei Seca ➔ 20 min Questões Cebraspe ➔ 10 min Revisão/Anki

---
## 🧭 Blocos Estratégicos de Conteúdo (Grafo Central)

### 🛠️ Bloco I: Ferramentas Técnicas e Instrumentais
* [[02 - MOC - Língua Portuguesa]]
	* *Tópicos de Impacto:* [[Interpretação de Textos]], [[Reescritura de Frases (Cebraspe)]].
* [[04 - Informática]]
	* *Conexões de Rede:* [[Internet vs Intranet]], [[Segurança da Informação]], [[Protocolos TCP-IP]].
* [[06 - Raciocínio Lógico Matemático]]
	* *Padrões de Engenharia:* [[Lógica de Proposições]], [[Diferença de Quadrados]], [[Análise Combinatória]].

### 🚨 Bloco II: O Peso de Elite (25% a 30% da Prova)
* [[01 - MOC - Legislação de Trânsito]]
	* *Foco Semanal:* [[Capítulo I - Disposições Preliminares]], [[Capítulo II - Do Sistema Nacional de Trânsito]] e [[Capítulo III - Normas Gerais de Circulação e Conduta]].
	* *Termos Críticos (Anexo I):* [[Caminhonete vs Camioneta]], [[Parada vs Estacionamento]], [[Classificação de Vias]].

### ⚖️ Bloco III: O Núcleo Jurídico e Administrativo
* [[03 - Direito Administrativo]]
	* *Nós Principais:* [[Agentes Públicos - Lei 8112]], [[Atos Administrativos - COFIFOMOB]], [[Poderes da Administração]].
* [[05 - MOC - Direito Constitucional]]
	* *Nós Principais:* [[Art. 5º - Direitos e Garantias Fundamentais]], [[Art. 144 - Segurança Pública (Atribuições PRF)]].

---

## 📊 Queries de Controle Automático (Dataview)
*Insira estes blocos abaixo se tiver o plugin Dataview ativo para monitorar o status das suas notas atômicas:*

```dataview
TABLE status, meta_acertos
FROM #PRF
SORT file.name ASC