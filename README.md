# Projeto: Live do Quinta com Dados - Conhecendo o LangFlow

## Descrição
Neste próximo encontro do **Quinta com Dados**, vamos mergulhar no LangFlow, um novo framework visual para a construção de aplicações multi-agente e RAG. Nesta live, **Igor do Nascimento** e **Allan Spadini** irão demonstrar como essa ferramenta open-source e customizável, baseada em Python, pode transformar suas ideias em soluções poderosas e reais.

## Participantes
- [Igor do Nascimento](https://www.linkedin.com/in/igor-nascimento-alves/)
- [Allan Spadini](https://www.linkedin.com/in/allan-spadini/)

## Data e Horário
- **Data:** 01 de agosto
- **Horário:** 18:00 - 19:00

## Links Importantes
- **LangFlow - Site Oficial:** [LangFlow](https://www.langflow.org/)
- **LangFlow - Documentação:** [Documentação LangFlow](https://docs.langflow.org/)
- **Groq - Site Oficial:** [Groq](https://groq.com/)
- **Recomendações de Cursos:**
  - [LangChain e Python: criando ferramentas com a LLM OpenAI](https://cursos.alura.com.br/course/langchain-python-ferramentas-llm-openai)
  - [LangChain: desenvolva agentes de inteligência artificial](https://cursos.alura.com.br/course/langchain-desenvolva-agentes-inteligencia-artificial)
  - [OpenAI e Python: crie ferramentas poderosas e chatbots inteligentes com as APIs da OpenAI](https://cursos.alura.com.br/formacao-openai-python-crie-ferramentas-chatbots-inteligentes-apis-openai)

## Setup do Projeto

### Requisitos
- Python 3.8+
- LangFlow 1.0.7

### Instalação

1. Crie e ative um ambiente virtual:
   ```bash
   python -m venv .venv
   .venv\Scripts\activate   # Windows
   source .venv/bin/activate  # Mac/Linux
   ```

2. Atualize o pip:
   ```bash
   python -m pip install --upgrade pip
   ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

4. Execute o LangFlow:
   ```bash
   python -m langflow run
   ```

### Estrutura do Projeto
- **dados/**: Contém arquivos de dados como `editar_de_abertura_n_01_2024.pdf` e `edita-menor.txt`.
- **flows/**: Contém `Live Langflow.json` com os fluxos do LangFlow.
- **setup.bat**: Script para setup do ambiente no Windows.
- **requirements.txt**: Arquivo com as dependências do projeto.
- **readme.md**: Documentação do projeto.