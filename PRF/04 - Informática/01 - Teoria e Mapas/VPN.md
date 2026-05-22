---
tags:
  - informatica
  - seguranca-da-informacao
  - redes
projeto: PRF
data_criacao: 2026-05-19
patch:
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