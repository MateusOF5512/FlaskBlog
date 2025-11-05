# 🧠 Análise de Qualidade de Software – Projeto Blog em Flask

Este repositório faz parte da disciplina **Análise e Qualidade de Software** e tem como objetivo **avaliar a qualidade de um projeto de blog desenvolvido em Flask**.  
⚠️ **Importante:** o grupo **não desenvolveu o blog**, apenas realizou a **análise de sua qualidade de software** com base em normas, métricas e boas práticas reconhecidas na engenharia de software.

---

## 🚀 Tecnologias Utilizadas no Sistema Avaliado

- 🐍 **Python 3.11+**
- 🌐 **Flask 3.0.3**
- 🗄️ **Flask-SQLAlchemy** — ORM para banco de dados  
- 🔒 **Flask-Bcrypt** — Criptografia de senhas  
- 👥 **Flask-Login** — Sistema de autenticação e sessão  
- 🧾 **Flask-WTF / WTForms** — Formulários com validação  
- 🖼️ **Pillow** — Manipulação de imagens  
- 📧 **email-validator** — Validação de e-mails

📦 As dependências estão listadas em [`requirements.txt`](./requirements.txt)

---

## 🛠️ Tutorial de Instalação (passo a passo)

Este guia mostra como criar um ambiente virtual, ativá-lo e instalar as dependências do projeto. As instruções incluem comandos para **Windows (cmd / PowerShell)** e **Linux / macOS (bash/zsh)**.

> **Pré-requisitos:** Python 3.8+ (recomendado 3.11+). Verifique com:
python --version
>
> ### Windows (PowerShell)
> 
> # criar venv
python -m venv nome_venv

# ativar venv
.\nome_venv\Scripts\Activate

# instalar dependecias com arquivo requirements.txt
pip install -r requirements.txt

# instalar dependecias com pip
pip install Flask==3.0.3 Flask-SQLAlchemy==3.1.1 Flask-Bcrypt==1.0.1 Flask-Login==0.6.3 Flask-WTF==1.2.1 WTForms==3.1.2 Pillow==10.4.0 MarkupSafe==2.1.5 email_validator==2.1.1


## Se direcionar a pagina raiz do projeto e rodar:
python run.py
