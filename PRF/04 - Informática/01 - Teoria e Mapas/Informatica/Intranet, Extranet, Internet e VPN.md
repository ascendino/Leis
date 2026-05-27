

## **Internet**


A Internet é o que acontece quando todas essas redes estão interconectadas e conseguem “conversar” umas com as outras.

Outro ponto importante: a Internet é uma rede #pública; mas cuidado: isso não significa que ela é gratuita. O que torna uma rede “pública” é o fato de estar aberta ao acesso de qualquer pessoa, desde que ela atenda a requisitos mínimos — como estar conectada a um provedor de Internet.

Na Internet, o que permite que todos os computadores “falem a mesma língua” são os protocolos de comunicação – especialmente aqueles da famosa Arquitetura #TCP/IP.

E como eu “entro” na Internet? Simples: você precisa estar conectado a uma das redes que fazem parte da Internet. E isso acontece, normalmente, por meio de uma empresa chamada provedor de Internet.
## **Intranet**

A Intranet é uma rede de computadores corporativa – privada, restrita e exclusiva a um público específico – que se utiliza de tecnologias, padrões e serviços comuns à internet com o intuito de compartilhar informações e recursos computacionais, além de melhorar a comunicação interna entre membros de uma organização.

Intranet utiliza as mesmas tecnologias da internet

As intranets podem se utilizar de tudo que a Internet dispõe – tudo que foi desenvolvido para utilização na internet pode ser utilizado pelas intranets de organizações de qualquer porte

A diferença é o acesso. A internet é #pública — qualquer um pode entrar. Já a intranet é #interna, limitada a um grupo específico.

A intranet não depende da internet para funcionar. Ela pode existir perfeitamente sem conexão externa. É claro que é bem mais comum que esteja conectada à internet — especialmente quando os colaboradores trabalham de locais diferentes; mas se uma organização quiser, ela pode manter sua intranet totalmente isolada do mundo exterior, funcionando apenas entre os computadores da rede local. Agora vem a parte bonita da história: a intranet melhora, e muito, a comunicação interna. Ela centraliza documentos, acelera processos, reduz o uso de papel e aproxima pessoas que estão em unidades diferentes ou até em cidades diferentes. Não é exagero dizer que a intranet ajuda a empresa a funcionar melhor — mais organizada, mais produtiva e mais integrada.
## **Extranet**

A Extranet é uma rede privada de computadores que funciona como uma extensão da Intranet, permitindo o acesso restrito a usuários externos de uma organização via Internet – em geral, parceiros, fornecedores e clientes.

Se eu estou tentando acessar a Intranet via Internet, então agora não chamamos mais de Intranet – chamamos de Extranet! Em outras palavras, nós podemos dizer genericamente que a Extranet é uma parte da Intranet estendida a usuários externos da organização! Podemos afirmar também que a Extranet é basicamente uma modalidade de acesso à Intranet!

Nós já sabemos que a extranet é apenas uma extensão da intranet. Logo, se alguém está acessando a extranet, ela estará também acessando a intranet.

Agora vamos falar rapidamente sobre as aplicabilidades de Extranets: permitir acesso remoto à Intranet empresarial para uso de vendedores com conexão remota; dar igualdade de condições para que duas ou mais empresas compartilhem informações de forma controlada; viabilizar aplicações inovadoras de B2B; melhorar as comunicações ao longo da cadeia de suprimentos; desenvolvimento de projetos colaborativos entre empresas; agilizar transações comerciais; etc.

## **VPN**

---
---
tags:
  - informatica
  - seguranca-da-informacao
  - redes
projeto: PR
F
data_criacao: 2026-05-19
---

# VPN (Virtual Private Network)

## 📌 1. Conceito Central
Tecnologia de Segurança da Informação que permite criar um **"túnel" lógico, protegido e criptografado** dentro de uma rede pública (como a Internet). 
* Permite o tráfego seguro de dados.
* Proporciona a sensação de "estar dentro" da rede corporativa (Intranet) mesmo à distância.

---

## 🛠️ 2. Mecanismo de Funcionamento
* **Encapsulamento (Tunelamento):** Processo de colocar um pacote de dados original dentro de outro pacote adequado para atravessar a Internet. O pacote externo protege/esconde o interno.
* **Pilares de Segurança Atendidos:**
	* **Confidencialidade:** Garantida por [[Criptografia]] (dados embaralhados).
	* **Integridade:** Mecanismos que detectam e descartam pacotes alterados no caminho.
	* **Autenticidade:** Confirmação de identidade (senhas, [[MFA]], certificados digitais).

---

## 🔄 3. Modelos de Aplicação (Cai em Prova)

### A. Remote Access (Acesso Remoto / Client-to-Site)
* **Como funciona:** O usuário remoto (ex: em Home Office) instala um software cliente, autentica-se e recebe um IP interno da rede da empresa.
* **Exemplo PRF:** Policial acessando o sistema interno da PRF de dentro de casa.

### B. Site-to-Site (Ponto a Ponto)
* **Como funciona:** Conexão permanente estabelecida diretamente entre roteadores/firewalls de duas redes distintas. É transparente para o usuário final.
* **Exemplo PRF:** Interligar a Superintendência da PRF de São Paulo diretamente com a Sede em Brasília.

---

## ⚠️ 4. Limitações e Pegadinhas do Cebraspe (Gatilhos de Erro)
* **Não é solução mágica:** Protege o canal de transmissão, mas **NÃO** protege o *endpoint* (dispositivo do usuário).
* **Malwares:** Se o computador tiver um [[Keylogger]] ou malware, os dados são roubados *antes* de entrarem no túnel da VPN.
* **Anonimato:** **NÃO** gera anonimato absoluto. O provedor da VPN ou o administrador da rede corporativa ainda conseguem ver e registrar os logs de acesso.
* **Ataques mitigados no Wi-Fi público:** Protege contra *ARP Spoofing*, *Man-in-the-middle* e *Sniffing* (captura de tráfego) no Wi-Fi local.

---

## 🔗 Conexões Relacionadas (Links do Obsidian)
* [[Modelo OSI]] -> Opera principalmente na camada de Rede (IPSec) ou Transporte/Aplicação (SSL/TLS).
* [[Segurança da Informação]]
* [[Firewall]] -> Trabalham juntos, mas Firewall filtra e VPN tunela.
