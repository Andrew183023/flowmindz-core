# FlowMindz Modular Core 🚀🧠

Este repositório contém o núcleo modular da plataforma **FlowMindz**, com integração total entre:

- ✅ **FlowOps**: Inteligência Fiscal e Tributária com IA (GPT-4)
- ✅ **FlowGov**: Radar Nacional de Licitações Públicas
- ✅ **Painel Vite**: Conectado ao backend com IA e PostgreSQL

---

## ⚙️ Requisitos

- Python 3.11+
- PostgreSQL ativo e configurado
- Chave da API OpenAI (GPT-4)
- Variáveis de ambiente `.env`

---

## 🚀 Como rodar localmente

```bash
git clone https://github.com/Andrew183023/flowmindz-modular-core-final-v2.git
cd flowmindz-modular-core-final-v2

python -m venv venv
# Ative o ambiente:
# Linux/Mac
source venv/bin/activate
# Windows
.\venv\Scripts\activate

pip install -r requirements.txt

# Execute o backend
uvicorn main:app --reload
