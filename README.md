# dio--genai-copilot-and-openai
Explorando os Recursos de IA Generativa com Copilot e OpenAI

Resolução dos seguintes exercícios:
- [Explore generative AI in Azure AI Foundry Portal](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/12-generative-ai.html)
- [Prepare for an AI development project](https://microsoftlearning.github.io/mslearn-ai-studio/Instructions/01-Explore-ai-studio.html)
  - Este exercício vem substituir o antigo **Explore Azure OpenAI**
- [Apply content filters to prevent the output of harmful content](https://microsoftlearning.github.io/mslearn-ai-studio/Instructions/06-Explore-content-filters.html)
  - Este exercício vem substituir o antigo **Explore content filters in Azure OpenAI**

 # Explore generative AI in Azure AI Foundry Portal
**Objetivo:** Explorar o "Chat playground" com GPT-4.0

<img width="675" height="525" alt="image" src="https://github.com/user-attachments/assets/9f46a15a-70e3-46f2-a2f1-e214f9d7625f" />

<img width="1607" height="827" alt="image" src="https://github.com/user-attachments/assets/34a59615-5c96-4ae3-abd3-7699a393e541" />

**Conclusões**: É muito significativo dar informação clara e precisa ao ChatBot, sendo bem específico sobre o que queremos que ele devolva e qual o formato em que a resposta deve ser devolvida. Pontos chave: sucinto, objetivo e especifico.
Se não o fizermos, o Chat vai tender a escrever demasiado texto que pode não ser relevante.

### Exemplos:
- "What three places do you recommend I stay in Paris to be within walking distance to historical attractions? **Explain your reasoning.**"
- "What are the top 10 sights to see in Paris? **Answer with a numbered list in order of popularity.**"

Um ChatBot pode também analisar qualquer fonte da Web que lhe seja indicada, como por exemplo:
- "Based on the information at **https://en.wikipedia.org/wiki/History_of_Paris**, what were the key events in the city's history?"

 # Prepare for an AI development project
 Este exercício consiste mais em explorar a criação de projetos no Azure AI Foundry, associar o recurso Azure OpenAI e observar as configurações no **Management Center**

 <img width="891" height="814" alt="image" src="https://github.com/user-attachments/assets/469f3c7c-1775-498e-a45c-737d49fec295" />

 <img width="873" height="797" alt="image" src="https://github.com/user-attachments/assets/804673ea-2a64-49d9-a951-61666dd36e1c" />

<img width="873" height="797" alt="image" src="https://github.com/user-attachments/assets/f5b267f1-8686-4145-8442-3071c45d0b66" />

Deu ainda para explorar o painel de **Setup** do Chat Playground onde é possível deixar instruções e contexto iniciais para que o modelo siga uma linha de "raciocinio".

<img width="835" height="728" alt="image" src="https://github.com/user-attachments/assets/34b0ab2c-44c0-4cd1-ae1a-a22e812b63e5" />

Explorando o modelo criado é fácil integrar numa solução .NET, por exemplo. O AI Foundry já mostra o código e disponibiliza os endpoints necessários para realizar a conexão.
<img width="1800" height="825" alt="image" src="https://github.com/user-attachments/assets/c195cc71-d58b-4848-b2fd-8c749eb4e99e" />

# Apply content filters to prevent the output of harmful content

