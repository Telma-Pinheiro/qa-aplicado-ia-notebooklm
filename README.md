# ⚽ Segundo Cérebro: André Hernan - Bastidores e Carreira com IA

##### 📖 Contexto e Objetivos
Este projeto é um **Caderno Temático** desenvolvido no **Google NotebookLM**. O objetivo é criar um "Segundo Cérebro" focado na carreira e no conteúdo do jornalista **André Hernan**. 

Como **Analista de Testes**, utilizei este desafio para validar a capacidade de extração de insights a partir de dados não estruturados (vídeos e textos), aplicando pensamento crítico na análise das respostas da IA e organizando informações relevantes sobre o mercado da bola e a trajetória do jornalista.


## 🔍 Curadoria de Fontes
Utilizei uma mistura de mídias para alimentar a inteligência do caderno:

### 📺 Conteúdo Audiovisual (YouTube)
* **Canal André Hernan**: [Acessar canal](https://www.youtube.com/@andrehernan)
* **Palmeiras e reforços 2026**: [Assistir vídeo](https://www.youtube.com/watch?v=m69QigzBJNs)
* **Roger Machado no São Paulo**: [Assistir vídeo](https://www.youtube.com/watch?v=tSbJA7138Wo)
* **Shorts FShow**: [Assistir vídeo](https://www.youtube.com/shorts/UZxxxJyV3AQ)

### 📄 Conteúdo Textual Complementar

* Matéria do portal Lance com análise de André Hernan sobre cenário do futebol brasileiro: [Acessar matéria](https://www.lance.com.br/fora-de-campo/andre-hernan-analisa-chances-da-selecao-brasileira-na-copa-do-mundo.html)
  
### 📄 Conteúdo Textual e Acadêmico
* [Perfil de André Hernan na Wikipédia](https://pt.wikipedia.org/wiki/Andr%C3%A9_Hernan#)
* [Artigo acadêmico sobre jornalismo esportivo (Even3)](https://static.even3.com/anais/558060.pdf?v=638978860389976287)

## 🧠 Engenharia de Prompts e "Cicatrizes"
#### Fase 1: Exploração
**Prompt 1:** "Qual data ele trouxe informação sobre lesão de calleri?"

> **Resposta da IA:** 
Com base nos registros das fontes e na data atual de março de 2026, a informação foi trazida em outubro de 2025 (período correspondente aos "5 meses atrás" indicados nos vídeos)
. André Hernan ressalta que os detalhes foram baseados em um boletim médico divulgado pelo São Paulo em uma sexta-feira

> **Prompt 2:** "o jornalista Andre Hernan torce para qual time?."
> **Resposta da IA:** André Hernan é torcedor do São Paulo FC
De acordo com as fontes, essa informação sobre o seu time do coração foi revelada de forma não intencional durante a participação do jornalista em um podcast
Embora ele seja torcedor declarado do Tricolor Paulista, sua atuação profissional é amplamente reconhecida pela cobertura imparcial de diversos clubes, especialmente os grandes de São Paulo como Palmeiras e Corinthians.
>
**Prompt 3:** "Quero que seja mais sucinto nessa resposta?
**Resposta da IA:**
  André Hernan é torcedor do São Paulo FC
. A informação foi revelada de forma não intencional durante a participação do jornalista em um podcast
. No âmbito profissional, ele é reconhecido pela imparcialidade e pelo acesso a informações de bastidores de diversos clubes

#### Fase 2: Extração Técnica
**Prompt:** "o jornalista Andre Hernan torce para qual time?."

* **Fase 3 (Refinamento):** "Diferencie o que é notícia confirmada de especulação de mercado nas fontes citadas".

### 🛠️ Cicatrizes (Troubleshooting):
* **Desafio:** A IA teve dificuldade em trazer a data certa da pergunta, ela até respondeu, mas não trouxe somente a data, trouxe informação sobre a lesão. Pedi pra ser sucinto. Até diminuiu a informação, mas ainda trouxe informações mais do que o suficiente. 
---

## 📚 Miniguia de Estudo (Entrega Final)

### Resumo Estruturado
O projeto sintetiza a transição de André Hernan da TV tradicional para o sucesso no YouTube, destacando sua rede de contatos ("insider") que permite antecipar movimentos de mercado em clubes como São Paulo e Palmeiras.

### Glossário de Conceitos
* **Insider:** Jornalista com fontes diretas e exclusivas nos bastidores.
* **Transição de Carreira Digital:** O movimento da mídia offline (Globo) para plataformas próprias (NWB/YouTube).
* **Troféu ACEESP:** Principal reconhecimento da crônica esportiva paulista, vencido repetidamente por Hernan.

### Prompts Reutilizáveis
> "Crie um resumo dos últimos 3 'furos' de reportagem presentes nestas fontes, destacando os clubes envolvidos."


