
# CrewAI Study  - Jornada de Aprendizado

## Visão Geral do Repositório

Este repositório documenta minha jornada de estudos e implementação prática utilizando o framework **CrewAI**. O objetivo é aplicar os conceitos de 
agentes, tarefas e processos colaborativos para construir sistemas de automação baseados em LLMs (Large Language Models).

Este repositório serve como um diário de bordo para acompanhar o progresso do curso da DIO e como um portfólio dos projetos desenvolvidos.

## O que Estudei (Tópicos Abordados)

Este repositório é dividido pelas principais etapas e conceitos aprendidos durante o curso:

### 1. Fundamentos do CrewAI
*   **Introdução ao CrewAI:** Entendimento da arquitetura de agentes e sua aplicação em workflows.
*   **Configuração Inicial:** Instalação e configuração do ambiente de desenvolvimento.
*   **Conceitos Chave:** Diferença entre Agents, Tasks, Crews e Processes.

### 2. Implementação Prática
*   **Definição de Agentes (Agents):** Como configurar papéis, habilidades e objetivos para cada agente.
*   **Criação de Tarefas (Tasks):** Definição de subtarefas que os agentes precisam executar.
*   **Definição de Processos (Processes):** Estabelecimento das regras de colaboração (Sequential, Hierarchical, etc.).
*   **Integração de Ferramentas (Tools):** Como conectar agentes a APIs externas ou outras funcionalidades.

### 3. Projetos e Exemplos
*   **Projeto Hands-On:** Explorando o Ecosistema CrewAI.
*   **Projeto Hands-On:** Contruindo Projetos com CreAI.
*   **Projeto Hands-On: Implementando Agentes e Tarefas:** Exemplo de um fluxo de pesquisa e análise de dados usando CrewAI.


## Configuração e Pré-requisitos

Para rodar os exemplos e projetos deste repositório, você precisará dos seguintes pré-requisitos:

### Ambiente de Desenvolvimento
*   **Python:** Versão 3.9+
*   **Ambiente Virtual:** Recomendado o uso de `poetry`, `venv` ou `conda`.

###  Dependências
Para instalar as bibliotecas necessárias, execute o seguinte comando no seu terminal:

```bash
pip install crewai openai python-dotenv
```

###  Variáveis de Ambiente
Este projeto utiliza variáveis de ambiente para gerenciar as chaves de API. Crie um arquivo chamado `.env` na raiz do projeto e adicione suas chaves:

```dotenv
# .env file
OPENAI_API_KEY="SUA_CHAVE_AQUI"
```

##  Como Executar os Exemplos

Para rodar os exemplos de código contidos neste repositório, siga estes passos:

1.  **Clone o repositório:**
    ```bash
    git clone [URL_DO_SEU_REPOSITORIO]
    cd [NOME_DA_PASTA]
    ```
2.  **Crie o ambiente virtual (opcional, mas recomendado):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Linux/macOS
    # ou venv\Scripts\activate  # No Windows
    ```
3.  **Instale as dependências:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Execute o script principal:**
    ```bash
    python main.py
    ```

##  Próximos Passos

O aprendizado sobre CrewAI é contínuo. Meus objetivos futuros incluem:

1.  **Avançar na Complexidade:** Implementar processos mais complexos (ex: *Reflection* ou *Self-Correction*).
2.  **Explorar Ferramentas:** Integrar mais ferramentas externas (Web Scraping, integração com bases de dados).
3.  **Portfólio:** Desenvolver um projeto final de ponta a ponta que demonstre a capacidade de orquestração completa do CrewAI.

##  Contato

Se você tiver alguma dúvida, sugestão ou quiser colaborar neste estudo, sinta-se à vontade para entrar em contato:



