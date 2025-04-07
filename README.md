
# Laboratórios de Fundamentos de IA no Azure

Este repositório contém a documentação de dois laboratórios práticos da trilha de Fundamentos de IA com Azure (AI-900).  
Os laboratórios exploram os serviços de **Fala (Speech)** e **Análise de Texto (Text Analysis)** utilizando a plataforma Azure AI Foundry.

---

## 🧪 Laboratório 1: Serviço de Fala (Speech)

🔗 [Link para o laboratório](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html)

### Objetivo
Explorar o serviço de Fala do Azure AI para realizar a transcrição automática de fala em texto.

### Etapas

1. **Criar um Projeto no Azure AI Foundry**
   - Acessar: [https://ai.azure.com](https://ai.azure.com)
   - Criar projeto e selecionar região (ex: East US).
   - Recursos provisionados automaticamente: AI services, AI hub, AI project, Storage, Key vault, Resource group.

2. **Acessar o Serviço de Fala**
   - Navegar até *AI Services* e selecionar o serviço *Speech*.

3. **Testar Transcrição em Tempo Real**
   - Usar o *Speech Playground*.
   - Carregar arquivo de áudio de exemplo: [`WhatAICanDo.m4a`](https://aka.ms/mslearn-speech-files).
   - Observar a transcrição automática gerada pela IA.

### Insights
- A transcrição em tempo real é bastante precisa e identifica sotaques e ruídos com boa confiança.
- Excelente para aplicações de acessibilidade, atendimento ao cliente e legendagem automática.

---

## 🧪 Laboratório 2: Análise de Texto (Text Analysis)

🔗 [Link para o laboratório](https://aka.ms/ai900-text-analysis)

### Objetivo
Explorar o serviço de Linguagem do Azure AI para:
- Extração de entidades nomeadas
- Extração de frases-chave
- Sumarização de textos

### Etapas

1. **Criar Projeto no Azure AI Foundry**
   - Acessar: [https://ai.azure.com](https://ai.azure.com)
   - Criar projeto com região "East US".

2. **Acessar o Language Playground**
   - Navegar até *Playgrounds* > *Language Playground*

3. **Extração de Entidades Nomeadas**
   - Ferramenta: *Extract named entities*
   - Texto exemplo sobre avaliação de hotel
   - Resultado: identificação de entidades como “The Royal Hotel”, “London”, “British Museum”, etc.

4. **Extração de Frases-Chave**
   - Ferramenta: *Extract key phrases*
   - Frases como "Clean rooms", "great location", "Michelin Star", foram destacadas.

5. **Sumarização de Texto**
   - Ferramenta: *Summarize text*
   - Resumo automático com os principais pontos da avaliação.

### Insights
- O serviço é capaz de extrair insights semânticos de textos complexos.
- Ideal para análise de sentimentos, reviews, e grandes volumes de feedback textual.

---

## ✅ Conclusão Geral

Os dois laboratórios demonstram como os serviços do Azure AI podem transformar dados não estruturados (áudio e texto) em informações úteis e acionáveis.  
Essas soluções são úteis em contextos como atendimento, acessibilidade, análise de opinião pública, entre outros.

---

📚 Recomendado para:
- Estudantes e entusiastas de IA
- Desenvolvedores iniciantes
- Profissionais que desejam aplicar IA sem necessidade de programação complexa
