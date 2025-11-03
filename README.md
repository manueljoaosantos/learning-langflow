# 🧠 Learning Langflow

Exploração prática do [Langflow](https://github.com/langflow-ai/langflow) — uma interface visual para construir fluxos com LLMs (Large Language Models) de forma modular, intuitiva e extensível.

Este repositório documenta estudos, testes e integrações realizados durante o processo de estudo da ferramenta.

---

## 🚀 Objetivo

- Compreender a arquitetura base do Langflow (nós, conexões, componentes e agentes).  
- Criar fluxos personalizados com LLMs (OpenAI, Groq, Azure, Anthropic, Amazon Bedrock).  
- Testar integrações com **n8n**, **Flowise** e ferramentas personalizadas.  
- Desenvolver e documentar **Custom Tools** (componentes Python e APIs).  

---

## 🧩 Estrutura do Repositório


```bash
learning-langflow/
├── docs/                 # Notas e tutoriais sobre o Langflow
├── examples/             # Exemplos de fluxos (JSON exportados)
├── integrations/         # Testes de integração com n8n, Flowise, APIs, etc.
├── custom_tools/         # Ferramentas personalizadas (Custom Components)
└── README.md             # Este ficheiro
```

---

## 🧱 Conceitos-Chave

### **Agente Básico**
- **Componente de Entrada de Chat:** Obtém a entrada do utilizador.  
- **Componente LLM:** Liga o fluxo ao modelo de linguagem (Groq, Azure OpenAI, Anthropic, etc).  
- **Componente de Saída de Chat:** Recebe a resposta e cria o objeto de mensagem.

---

## ⚙️ Requisitos

- Python 3.10+  
- Langflow >= 1.0  
- Node.js (para integrações com Flowise/n8n)  

Instalação recomendada (em ambiente virtual):

```bash
python -m venv .venv
source .venv/bin/activate
pip install langflow

```

Para correr localmente:
```bash
langflow run
```

🧪 Exemplos

Fluxo simples de chat com Groq + OpenAI:
```bash
examples/chat-basic.json
```
Integração com n8n via webhook personalizado:

```bash
integrations/n8n_webhook/

```
📚 Recursos Úteis

🌐 Langflow Documentation
