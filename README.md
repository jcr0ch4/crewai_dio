#  CrewAI Study - Jornada de Aprendizado

##  Visão Geral do Repositório

Este repositório documenta minha jornada de estudos e implementação prática utilizando o framework **CrewAI**. O objetivo é aplicar os conceitos de agentes, tarefas e processos colaborativos para construir sistemas de automação baseados em LLMs (Large Language Models).

Este repositório serve como um diário de bordo para acompanhar o progresso do curso da DIO e como um portfólio dos projetos desenvolvidos.

---

##  O que Estudei (Tópicos Abordados)

Este repositório é dividido pelas principais etapas e conceitos aprendidos durante o curso:

### 1. Fundamentos do CrewAI
- **Introdução ao CrewAI:** Entendimento da arquitetura de agentes e sua aplicação em workflows.
- **Configuração Inicial:** Instalação e configuração do ambiente de desenvolvimento.
- **Conceitos Chave:** Diferença entre Agents, Tasks, Crews e Processes.

### 2. Implementação Prática
- **Definição de Agentes (Agents):** Como configurar papéis, habilidades e objetivos para cada agente.
- **Criação de Tarefas (Tasks):** Definição de subtarefas que os agentes precisam executar.
- **Definição de Processos (Processes):** Estabelecimento das regras de colaboração (Sequential, Hierarchical, etc.).
- **Integração de Ferramentas (Tools):** Como conectar agentes a APIs externas ou outras funcionalidades.

### 3. Projetos e Exemplos
- **Projeto Hands-On:** Explorando o Ecosistema CrewAI.
- **Projeto Hands-On:** Construindo Projetos com CrewAI.
- **Projeto Hands-On: Implementando Agentes e Tarefas:** Exemplo de um fluxo de pesquisa e análise de dados usando CrewAI.

---

##  Roteiro de Estudos (Módulos do Curso DIO)

### 1. Introdução aos Fundamentos do CrewAI

| Módulo | Duração | Status |
|--------|---------|--------|
| Como Você Vai Dominar os Fundamentos do CrewAI | 04:48 | ✅ CONCLUÍDO |
| Visão Geral do Ecossistema CrewAI | 08:05 | ⏳ EM ANDAMENTO |
| Projeto Hands-On: Explorando o Ecossistema CrewAI | 15:15 | ⏳ PENDENTE |
| Questionário: Visão Geral do Ecossistema CrewAI | 3 questões | ⏳ PENDENTE |

### 2. Componentes Principais de Projetos CrewAI

| Módulo | Duração | Status |
|--------|---------|--------|
| Desvendando os Componentes de Projetos CrewAI | 07:50 | ⏳ PENDENTE |
| Projeto Hands-On: Construindo Projetos com CrewAI | 27:21 | ⏳ PENDENTE |
| Questionário: Componentes Principais de Projetos CrewAI | 4 questões | ⏳ PENDENTE |

### 3. Conceitos de Agentes, Tarefas e Papéis

| Módulo | Duração | Status |
|--------|---------|--------|
| Entendendo Agentes, Tarefas e Papéis no CrewAI | 07:39 | ⏳ PENDENTE |
| Projeto Hands-On: Implementando Agentes e Tarefas | 26:55 | ⏳ PENDENTE |
| Questionário: Conceitos de Agentes, Tarefas e Papéis | 5 questões | ⏳ PENDENTE |

### 4. Aplicações Práticas e Benefícios do CrewAI

| Módulo | Duração | Status |
|--------|---------|--------|
| Aplicando CrewAI: Exemplos e Vantagens Competitivas | 08:43 | ⏳ PENDENTE |
| Projeto Hands-On: Explorando Benefícios do CrewAI | 09:06 | ⏳ PENDENTE |
| Questionário: Aplicações Práticas e Benefícios do CrewAI | - | ⏳ PENDENTE |

---

##  Configuração e Pré-requisitos

Para rodar os exemplos e projetos deste repositório, você precisará dos seguintes pré-requisitos:

###  Ambiente de Desenvolvimento
- **Python:** Versão 3.8+
- **Poetry** (recomendado) ou `venv`/`conda`

###  Dependências

#### Usando Poetry (Recomendado)
```bash
# Instalar todas as dependências
poetry install

# Executar scripts
poetry run python seu_script.py
```

#### Usando pip
```bash
# Instalar dependências manualmente
pip install crewai openai python-dotenv
```

###  Variáveis de Ambiente

Este projeto utiliza variáveis de ambiente para gerenciar as chaves de API. Crie um arquivo chamado `.env` na raiz do projeto:

```dotenv
# .env file
OPENAI_API_KEY="SUA_CHAVE_AQUI"
```

---

##  Como Executar os Exemplos

Para rodar os exemplos de código contidos neste repositório, siga estes passos:

1. **Clone o repositório:**
   ```bash
   git clone [URL_DO_SEU_REPOSITORIO]
   cd [NOME_DA_PASTA]
   ```

2. **Crie e ative o ambiente virtual:**
   ```bash
   # Usando venv
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   # ou venv\Scripts\activate  # Windows

   # Ou usando Poetry
   poetry shell
   ```

3. **Instale as dependências:**
   ```bash
   # Usando pip
   pip install -r requirements.txt

   # Usando Poetry
   poetry install
   ```

4. **Configure as variáveis de ambiente:**
   ```bash
   cp .env.example .env
   # Edite o arquivo .env com suas chaves de API
   ```

5. **Execute o script principal:**
   ```bash
   python main.py
   # ou
   poetry run python main.py
   ```

---

##  Estrutura do Projeto

```
crewai-study/
├── src/
│   ├── agents/          # Definição dos agentes
│   ├── tasks/           # Definição das tarefas
│   ├── crews/           # Configuração dos crews
│   └── tools/           # Ferramentas personalizadas
├── notebooks/           # Jupyter notebooks para experimentos
├── tests/              # Testes unitários
├── data/               # Dados de exemplo
├── .env                # Variáveis de ambiente
├── pyproject.toml      # Configuração Poetry
├── requirements.txt    # Dependências pip
└── README.md          # Este arquivo
```

---

##  Próximos Passos

O aprendizado sobre CrewAI é contínuo. Meus objetivos futuros incluem:

1. **Avançar na Complexidade:** Implementar processos mais complexos (ex: *Reflection* ou *Self-Correction*).
2. **Explorar Ferramentas:** Integrar mais ferramentas externas (Web Scraping, integração com bases de dados).
3. **Portfólio:** Desenvolver um projeto final de ponta a ponta que demonstre a capacidade de orquestração completa do CrewAI.
4. **Compartilhar Conhecimento:** Criar tutoriais e artigos sobre as melhores práticas com CrewAI.

---

##  Roadmap de Aprendizado

- [x] Introdução aos fundamentos do CrewAI
- [ ] Configuração do ambiente de desenvolvimento
- [ ] Criação do primeiro agente
- [ ] Definição de tarefas e processos
- [ ] Integração com ferramentas externas
- [ ] Projeto prático completo
- [ ] Documentação e compartilhamento

---

##  Como Contribuir

Contribuições são bem-vindas! Se você tem sugestões, correções ou ideias para novos projetos:

1. Faça um fork do repositório
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

---

##  Licença

Este projeto está sob a licença GNU - veja o arquivo [LICENSE](LICENSE) para detalhes.

---

##  Contato

Se você tiver alguma dúvida, sugestão ou quiser colaborar neste estudo, sinta-se à vontade para entrar em contato


---

##  Agradecimentos

- [DIO](https://www.dio.me/) pelo curso e material de estudo
- [CrewAI](https://www.crewai.com/) pelo framework incrível
- Comunidade open-source pelo suporte e colaboração

---

<div align="center">
  <sub>Built with ❤️ during the CrewAI Study Journey</sub>
</div>
```
