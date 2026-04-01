# ⚽ Segundo Cérebro com IA: Análise de Bastidores e Carreira de André Hernan

##### 📖 Contexto e Objetivos
Este projeto é um **Caderno Temático** desenvolvido no **Google NotebookLM**. O objetivo é criar um "Segundo Cérebro" focado na carreira e no conteúdo do jornalista **André Hernan**. 

Como **Analista de Testes**, utilizei este desafio para validar a capacidade de extração de insights a partir de dados não estruturados (vídeos e textos), aplicando pensamento crítico na avaliação da qualidade das respostas da IA e organizando informações relevantes sobre o mercado da bola e a trajetória do jornalista.


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
**Prompt 1:** "Qual data ele trouxe informação sobre "lesão de Calleri?"

> **Resposta da IA:** 
Com base nos registros das fontes e na data atual de março de 2026, a informação foi trazida em outubro de 2025 (período correspondente aos "5 meses atrás" indicados nos vídeos)
. André Hernan ressalta que os detalhes foram baseados em um boletim médico divulgado pelo São Paulo em uma sexta-feira

> **Prompt 2:** "O jornalista Andre Hernan torce para qual time?"

> **Resposta da IA:**
André Hernan é torcedor do São Paulo FC
De acordo com as fontes, essa informação sobre o seu time do coração foi revelada de forma não intencional durante a participação do jornalista em um podcast
Embora ele seja torcedor declarado do Tricolor Paulista, sua atuação profissional é amplamente reconhecida pela cobertura imparcial de diversos clubes, especialmente os grandes de São Paulo como Palmeiras e Corinthians.
>
**Prompt 3 (Refinamento):** "Quero que seja mais sucinto nessa resposta?"

**Resposta da IA:**
  André Hernan é torcedor do São Paulo FC
. A informação foi revelada de forma não intencional durante a participação do jornalista em um podcast
. No âmbito profissional, ele é reconhecido pela imparcialidade e pelo acesso a informações de bastidores de diversos clubes

### 🔄 Variações e Refinamentos de Prompt

Além das perguntas diretas, foram utilizados prompts mais analíticos para avaliar a capacidade da IA de interpretar e classificar informações:

**Prompt:** "Diferencie o que é notícia confirmada de especulação de mercado nas fontes citadas."

> **Resposta da IA:**
Nas fontes citadas, é possível distinguir os fatos já concretizados e oficiais das movimentações que ainda pertencem ao campo das sondagens, desejos ou planejamento estratégico.

**Notícias Confirmadas:**
- Mudanças de comando, como a saída de treinadores e novas contratações
- Boletins médicos oficiais divulgados por clubes
- Transferências concluídas de jogadores
- Informações documentadas sobre carreira profissional
- Parcerias e contratos de marketing

**Especulações e Planejamento de Mercado:**
- Planejamento futuro de contratações
- Sondagens e interesses não concretizados
- Negociações inexistentes apesar de boatos
- Rumores e projeções sobre jogadores

**Análise:**

A IA demonstrou boa capacidade de estruturar e classificar as informações em categorias claras, separando fatos confirmados de especulações. No entanto, a resposta ainda apresenta generalizações e não evidencia claramente a origem de cada informação nas fontes, o que pode impactar a rastreabilidade e a precisão da análise.

### 🛠️ Cicatrizes (Troubleshooting):
* **Desafio:** Identifiquei uma falha na assertividade de dados pontuais: o modelo apresentou dificuldade em respeitar a restrição de formato (retornar apenas a data), apresentando informações excedentes mesmo após o refinamento do prompt para concisão.

## 🧪 Aplicação de QA na Análise com IA

Durante o desenvolvimento do projeto, apliquei conceitos de QA (Qualidade de Software) na interação com a IA, indo além da simples consulta de informações.

### 🔍 Análise e Organização de Dados
A partir de dados não estruturados (vídeos e textos), realizei a interpretação, avaliação e organização das informações, extraindo apenas os pontos relevantes para análise.

Essa abordagem é semelhante ao trabalho de um Analista de Testes ao lidar com requisitos e logs de sistema, que muitas vezes são incompletos ou pouco claros. Assim como nos logs, onde é necessário interpretar mensagens técnicas e correlacioná-las com o contexto para identificar problemas, neste projeto foi preciso analisar as respostas da IA, filtrar informações excessivas e identificar os dados realmente úteis.

Dessa forma, apliquei um raciocínio investigativo para transformar informações dispersas em conhecimento estruturado.

### 🧠 Validação de Respostas da IA
Foram identificados alguns comportamentos relevantes da IA:
- Respostas excessivamente verbosas
- Falta de objetividade em perguntas específicas
- Dificuldade em retornar apenas dados pontuais (ex: datas)

Esses pontos foram analisados como critérios de qualidade das respostas.

### 🔄 Teste Iterativo de Prompts
A interação com a IA seguiu um ciclo semelhante ao processo de testes:
- Definição do prompt inicial
- Análise da resposta obtida
- Refinamento do prompt
- Nova validação da resposta

### 🚀 Conexão com QA para IA Generativa
O projeto também demonstra conceitos iniciais de QA aplicado à IA, como:
- Validação de respostas de modelos
- Avaliação de precisão e objetividade
- Redução de ambiguidades via refinamento de prompts

## 📚 Miniguia de Estudo (Entrega Final)

### Resumo Estruturado
O projeto sintetiza a transição de André Hernan da TV tradicional para o sucesso no YouTube, destacando sua rede de contatos ("insider") que permite antecipar movimentos de mercado em clubes como São Paulo e Palmeiras.

### Glossário de Conceitos
* **Insider:** Jornalista com fontes diretas e exclusivas nos bastidores.
* **Transição de Carreira Digital:** O movimento da mídia offline (Globo) para plataformas próprias (NWB/YouTube).
* **Troféu ACEESP:** Principal reconhecimento da crônica esportiva paulista, vencido repetidamente por Hernan.

### Prompts Reutilizáveis
> "Crie um resumo dos últimos 3 'furos' de reportagem presentes nestas fontes, destacando os clubes envolvidos."


