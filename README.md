# Desafio Prático - Introdução à Inteligência Artificial

Análise Exploratória de Dados (AED) do conjunto de dados da Uber disponibilizado no Kaggle.

## 📋 Descrição

Este projeto realiza uma análise exploratória de dados (AED) utilizando o dataset "uber-ride-analytics-dashboard" do Kaggle, explorando padrões de utilização do serviço, variações temporais e características das corridas.

**Dataset:** [Uber Ride Analytics Dashboard](https://www.kaggle.com/datasets/yashdevladdha/uber-ride-analytics-dashboard/data)

## 🔧 Pré-requisitos

- Python 3.12 ou superior instalado
- Git (opcional, para clonar o repositório)
- Conexão com internet (para baixar as dependências)

## 🚀 Como configurar o ambiente

### 1. Clone ou baixe o projeto

```bash
git clone https://github.com/Doglaum/teste-sctec-inteligencia-artifical.git
cd desafio_pratico_inteligencia_artificial
```

### 2. Crie o ambiente virtual

No Windows (PowerShell):
```powershell
python -m venv .venv
```

No Linux/Mac:
```bash
python3 -m venv .venv
```

### 3. Ative o ambiente virtual

No Windows (PowerShell):
```powershell
.venv\Scripts\Activate.ps1
```

No Windows (CMD):
```cmd
.venv\Scripts\activate.bat
```

No Linux/Mac:
```bash
source .venv/bin/activate
```

> ⚠️ **Importante:** Você deve ver `(.venv)` no início do prompt do terminal quando o ambiente estiver ativo.

### 4. Instale as dependências

```bash
pip install -r requirements.txt
```

## 📦 Bibliotecas utilizadas

- **pandas** - Manipulação e análise de dados
- **matplotlib** - Visualização de dados (gráficos e plots)
- **jupyter/notebook** - Ambiente interativo para análise exploratória

## 📂 Estrutura do projeto

```
desafio_pratico_inteligencia_artificial/
│
├── .venv/                  # Ambiente virtual (não versionar)
├── ncr_ride_bookings.csv   # Dataset das corridas da Uber
├── teste_pratico.ipynb     # Notebook com a análise exploratória
├── requirements.txt        # Dependências do projeto
├── .gitignore             # Arquivos ignorados pelo Git
└── README.md              # Este arquivo
```

## 🎯 Como usar

### Executar a análise exploratória

1. Certifique-se de que o ambiente virtual está ativado (`(.venv)` no prompt)

2. Inicie o Jupyter Notebook:
```bash
jupyter notebook
```

3. O navegador abrirá automaticamente. Abra o arquivo `teste_pratico.ipynb`

4. Execute as células sequencialmente (Shift + Enter) para visualizar a análise

## ⚙️ Desativando o ambiente virtual

Quando terminar de trabalhar no projeto:

```bash
deactivate
```

## 👥 Compartilhando o projeto

**Nunca** commite a pasta `.venv/` no Git. Ela está incluída no `.gitignore`.

Outras pessoas devem:
1. Clonar o repositório
2. Criar seu próprio ambiente virtual (passo 2)
3. Ativar o ambiente (passo 3)
4. Instalar as dependências (passo 4)

## 📝 Notas

- O ambiente virtual isola as dependências do projeto
- Cada projeto pode ter versões diferentes das mesmas bibliotecas
- Sempre ative o ambiente virtual antes de trabalhar no projeto
- A pasta `.venv/` pode ser deletada e recriada sem perder código

## 🆘 Problemas comuns

### "Não consigo ativar o ambiente virtual no PowerShell"
Execute antes:
```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```

### "pip não encontrado"
Certifique-se de que o Python está instalado e no PATH do sistema.

### "Módulo não encontrado"
Verifique se o ambiente virtual está ativo (`(.venv)` no prompt) e execute:
```bash
pip install -r requirements.txt
```

---

**Desenvolvido para o curso:** Introdução à Inteligência Artificial (IP 20h A) - SENAI/SC LAB365
