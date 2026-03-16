Triagem de Reclamações com IA e n8n
Sistema autônomo de Customer Experience (CX) que utiliza Inteligência Artificial para classificar, registrar e priorizar atendimentos em tempo real.

Tecnologias Utilizadas

* **n8n** 
* **Google Gemini 2.5 Flash**
* **Google Sheets API** 
* **Gmail API** 
* **JavaScript** 

A Solução

O fluxo recebe dados via **Webhook**, processa o texto através de um modelo de linguagem (LLM) que identifica o sentimento do cliente e atribui uma nota de urgência de 1 a 5. 
1. **Casos Críticos (Urgência >= 4):** Disparam um alerta imediato via e-mail para a equipe de suporte.
2. **Todos os Casos:** São registrados automaticamente em uma planilha para posterior análise de BI.
