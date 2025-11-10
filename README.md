# 🚀 Chat DeepSeek — Rode a IA localmente com Ollama, Streamlit e ngrok  

[![Python](https://img.shields.io/badge/Python-3.11%2B-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-App-red?logo=streamlit&logoColor=white)](https://streamlit.io)
[![Ollama](https://img.shields.io/badge/Ollama-Local%20AI-black?logo=ollama&logoColor=white)](https://ollama.ai)
[![ngrok](https://img.shields.io/badge/ngrok-Tunnel-green?logo=ngrok&logoColor=white)](https://ngrok.com)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Asimov Academy](https://img.shields.io/badge/Asimov%20Academy-AI%20Learning-orange)](https://asimov.academy)

> **Por [Asimov Academy](https://asimov.academy) | Projeto prático de IA aplicada**  

---

## 💡 Sobre o projeto  

Bem-vindo ao **Chat DeepSeek**, um projeto criado para te ensinar a rodar o **modelo DeepSeek** localmente — direto no seu computador, sem depender de servidores externos.  

Aqui, você vai aprender a:  

1. ⚙️ **Rodar o DeepSeek com o Ollama**, gerenciando o modelo de IA localmente;  
2. 💬 **Criar uma interface de chat funcional e moderna com Streamlit**;  
3. 🌐 **Disponibilizar seu app online com ngrok**, acessível de qualquer lugar — até do celular.  

---

## 🧠 Por que este projeto é importante  

Em um momento em que quase toda IA roda em nuvem, o **Chat DeepSeek** mostra o poder de **ter um modelo avançado de linguagem rodando localmente**, com total **autonomia e privacidade**.  

✅ **Privacidade garantida:** seus dados nunca saem do seu computador.  
⚡ **Performance sob medida:** aproveite os recursos da sua própria máquina.  
🔧 **Controle total:** customize, integre e escale do seu jeito.  

Este projeto é ideal para quem quer **entender os bastidores da IA moderna** e dominar o ciclo completo — da instalação à publicação.  

---

## 🧰 Tecnologias utilizadas  

- [Python 3.11+](https://www.python.org/)  
- [Ollama](https://ollama.ai) — gerenciamento local de modelos de IA  
- [Streamlit](https://streamlit.io) — criação da interface de chat  
- [ngrok](https://ngrok.com) — exposição do app na web  
- [DeepSeek](https://www.deepseek.com/) — modelo de linguagem  

---

## ⚙️ Instalação  

Clone este repositório:  
```bash
git clone https://github.com/seuusuario/chat-deepseek.git
cd chat-deepseek
Crie e ative um ambiente virtual:

bash
Copiar código
python -m venv .venv
source .venv/bin/activate   # Linux/Mac
# ou
.venv\Scripts\activate      # Windows
Instale as dependências:

bash
Copiar código
pip install -r requirements.txt
🧠 Configurando o DeepSeek com Ollama
Baixe e instale o Ollama:
👉 https://ollama.ai/download

Depois, baixe o modelo DeepSeek:

bash
Copiar código
ollama pull deepseek
Para testar localmente:

bash
Copiar código
ollama run deepseek
Se tudo estiver funcionando, o modelo estará pronto para integração com o Streamlit.

💬 Executando a interface com Streamlit
Inicie o servidor local com:

bash
Copiar código
streamlit run app.py
Acesse no navegador:
👉 http://localhost:8501

Agora você já pode conversar com o DeepSeek localmente 🚀

🌍 Publicando com ngrok
Para compartilhar seu app online, basta conectar o ngrok à porta 8501:

bash
Copiar código
ngrok http 8501
O terminal exibirá uma URL pública, como:

arduino
Copiar código
https://xxxx-xx-xx-xx-xx.ngrok-free.app
📲 Acesse essa URL de qualquer dispositivo — até mesmo do seu celular!

🧩 Estrutura do projeto
bash
Copiar código
chat-deepseek/
├── app.py                # Interface Streamlit
├── requirements.txt      # Dependências do projeto
├── README.md             # Este arquivo :)
└── assets/               # (opcional) Imagens e recursos visuais
🚀 Resultados
Ao final, você terá um chat de IA 100% local, rápido, seguro e acessível de qualquer lugar.
Um projeto perfeito para quem quer aprender IA de forma prática e independente.

🧑‍💻 Conclusão
O Chat DeepSeek é mais do que um projeto técnico — é um manifesto de autonomia em Inteligência Artificial.
Com ele, você entende como trazer o poder da IA para dentro da sua rotina, controlando cada parte do processo: do modelo ao deploy.

🧭 Domine a IA local.
🌎 Compartilhe com o mundo.
💡 Inspire outros desenvolvedores.
