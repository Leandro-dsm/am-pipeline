# AM Pipeline

Pipeline de processamento e análise de dados desenvolvido em Python.

## 📋 Sobre o Projeto

Este projeto implementa um pipeline de dados utilizando Python, com foco em processamento, transformação e análise de dados.

## 🛠️ Tecnologias Utilizadas

- **Python** — linguagem principal do projeto
- **uv** — gerenciador de pacotes e ambientes virtuais
- **Jupyter Notebook** — para exploração e desenvolvimento
- **Git/GitHub** — controle de versão

## 📁 Estrutura do Projeto

- `src/am_pipeline/` — Código-fonte principal do pipeline
- `01_pipeline_inicial.ipynb` — Notebook com a pipeline inicial
- `pyproject.toml` — Configurações e dependências do projeto
- `uv.lock` — Lockfile de dependências (uv)
- `.python-version` — Versão do Python utilizada
- `.gitignore` — Arquivos ignorados pelo Git
- `README.md` — Este arquivo

## 🚀 Como Executar

### Pré-requisitos

- Python instalado (versão indicada em `.python-version`)
- [uv](https://github.com/astral-sh/uv) instalado

### Instalação

1. Clone o repositório:

git clone https://github.com/Leandro-dsm/am-pipeline.git
cd am-pipeline

2. Instale as dependências com o `uv`:

uv sync

3. (Opcional) Ative o ambiente virtual:

Windows:
.venv\Scripts\activate

Linux/Mac:
source .venv/bin/activate

### Executando o pipeline

Abra o notebook `01_pipeline_inicial.ipynb` no VS Code ou Jupyter:

uv run jupyter notebook

Ou execute diretamente pelo VS Code.

## 📝 Licença

Este projeto está sob a licença MIT.

## 👤 Autor

**Leandro**
- GitHub: [@Leandro-dsm](https://github.com/Leandro-dsm)

---

⭐ Se este projeto foi útil para você, considere dar uma estrela!
