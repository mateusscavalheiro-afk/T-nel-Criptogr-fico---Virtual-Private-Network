# Simulador Interativo: VPN & Criptografia

Este repositório contém uma aplicação web interativa desenvolvida para demonstrar, de forma prática e gamificada, o funcionamento de uma **VPN (Virtual Private Network)** e os conceitos fundamentais de segurança da informação.

## 🚀 Sobre o Projeto
O simulador permite visualizar em tempo real a diferença entre uma conexão desprotegida e uma conexão via túnel criptografado. Através de um "minigame" de terminal, o usuário pode:
* Observar a interceptação de pacotes por agentes maliciosos.
* Entender o processo de encapsulamento e proteção de dados.
* Visualizar a descriptografia técnica na ponta destino.

## 📚 Conceitos Fundamentais

### O que é uma VPN?
Uma VPN cria um túnel criptografado entre dois pontos na World Wide Web, garantindo a **privacidade** e a **segurança** dos dados trafegados contra interceptações (como hackers ou espionagem).

### O que é Criptografia?
É o processo de transformar informações legíveis em dados ilegíveis para garantir que apenas o remetente e o destinatário possam "abrir" o pacote de dados, utilizando chaves públicas e privadas para este fim.

---

## 📖 Manual do Apresentador: Glossário Técnico

Este guia explica os elementos representados na simulação:

* **Túnel VPN:** Canal virtual isolado que encapsula o tráfego dentro da rede pública, protegendo os dados.
* **Criptografia AES-256:** Processo de embaralhamento de dados com padrão robusto; levaria bilhões de anos para ser quebrado por força bruta.
* **Hacker:** O agente malicioso que tenta interceptar pacotes na rede pública (redes abertas).
* **Protocolo RSA:** Lógica matemática baseada em chaves pública e privada para troca segura de informações.
* **Chave Pública:** O "cadeado" aberto distribuído para que outros possam trancar (criptografar) a mensagem.
* **Chave Privada:** A "única cópia da chave" secreta, usada exclusivamente pelo destinatário para abrir (descriptografar) o cofre.
* **Servidor Destino (Empresa):** O ponto final que recebe a mensagem e a restaura ao formato original.
* **Descriptografia:** Etapa onde a chave privada é aplicada para reverter o embaralhamento e revelar a mensagem original.
* **ISP (Provedor de Internet):** Intermediário que identifica a existência da conexão (túnel), mas é impedido pela criptografia de ler o conteúdo.
* **Latência:** O tempo de processamento adicionado à transação, representando o custo computacional da segurança (criptografia).

---

## 🛠️ Tecnologias Utilizadas
* **HTML5 / CSS3:** Estrutura e animações personalizadas.
* **JavaScript (Web Audio API):** Síntese de áudio 8-bits nativa para feedback sonoro da simulação.
* **GitHub Pages:** Deploy e hospedagem do projeto.

## 💡 Como usar
1. Acesse o link do projeto hospedado no GitHub Pages.
2. Ative a chave **VPN ON** para iniciar o encapsulamento.
3. Envie uma mensagem e observe a jornada do pacote, a tentativa de interceptação e a descriptografia final pelo servidor.

---
*Projeto desenvolvido para fins educacionais sobre Tecnologias da Segurança da Informação.*
