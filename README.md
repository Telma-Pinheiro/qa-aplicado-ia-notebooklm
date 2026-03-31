# ⚽ Segundo Cérebro: André Hernan - Bastidores e Carreira com IA

## 📖 Contexto e Objetivos
Este projeto é um **Caderno Temático** desenvolvido no **Google NotebookLM**. O objetivo é criar um "Segundo Cérebro" focado na carreira e no conteúdo do jornalista **André Hernan**. 

Como **Analista de Testes**, apliquei este desafio para validar a extração de *insights* de uma massa de dados não estruturada (vídeos e textos), organizando informações sobre o mercado da bola e a trajetória profissional do jornalista.

---

## 🔍 Curadoria de Fontes
Utilizei uma mistura de mídias para alimentar a inteligência do caderno:

### 📺 Conteúdo Audiovisual (YouTube)
* **Canal André Hernan**: https://www.youtube.com/@andrehernan
* **Palmeiras e reforços 2026**: https://www.youtube.com/watch?v=m69QigzBJNs
* **Roger Machado no São Paulo**: https://www.youtube.com/watch?v=tSbJA7138Wo
* **Shorts FShow**: https://www.youtube.com/shorts/UZxxxJyV3AQ

### 📄 Conteúdo Textual e Acadêmico
* **Wikipédia - André Hernan**: https://pt.wikipedia.org/wiki/Andr%C3%A9_Hernan#
* **Artigo Even3 (Análise)**: https://static.even3.com/anais/558060.pdf?v=638978860389976287

---

## 🧠 Engenharia de Prompts e "Cicatrizes"

### Estratégia de Prompts:
* **Fase 1 (Exploração):** "Quem é André Hernan e qual sua importância no jornalismo esportivo?".
* **Fase 2 (Extração Técnica):** "Com base nos vídeos, liste as negociações do Palmeiras para 2026 e o status de cada uma".
* **Fase 3 (Refinamento):** "Diferencie o que é notícia confirmada de especulação de mercado nas fontes citadas".

### 🛠️ Cicatrizes (Troubleshooting):
* **Desafio:** A IA teve dificuldade em separar notícias de 2025 e 2026 nos primeiros testes.
* **Solução:** Inclusão de um comando de contexto temporal, exigindo que a IA citasse a data da fonte antes de cada resposta.

---

## 📚 Miniguia de Estudo (Entrega Final)

### Resumo Estruturado
O projeto sintetiza a transição de André Hernan da TV tradicional para o sucesso no YouTube, destacando sua rede de contatos ("insider") que permite antecipar movimentos de mercado em clubes como São Paulo e Palmeiras.

### Glossário de Conceitos
* **Insider:** Jornalista com fontes diretas e exclusivas nos bastidores.
* **Transição de Carreira Digital:** O movimento da mídia offline (Globo) para plataformas próprias (NWB/YouTube).
* **Troféu ACEESP:** Principal reconhecimento da crônica esportiva paulista, vencido repetidamente por Hernan.

### Prompts Reutilizáveis
> "Crie um resumo dos últimos 3 'furos' de reportagem presentes nestas fontes, destacando o clube envolvido."

---
*Projeto desenvolvido para o bootcamp da DIO - 2026.*
