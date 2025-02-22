# 🎯 YouTube Playlist Bot

Este projeto é um script automatizado com Selenium para criar playlists no YouTube com vídeo-aulas organizadas por matéria de vestibular! 🚀

## 🛠️ **Tecnologias Utilizadas**
- Python
- Selenium
- WebDriver Manager

## 📂 **Estrutura do Projeto**
- `main.py`: Código principal para buscar vídeos e criar playlists.
- `requirements.txt`: Dependências do projeto.

## ⚙️ **Configuração do Ambiente**
1. Clone o repositório:
```bash
  git clone https://github.com/seu-usuario/youtube-playlist-bot.git
  cd youtube-playlist-bot
```

2. Crie um ambiente virtual (opcional, mas recomendado):
```bash
  python -m venv venv
  source venv/bin/activate  # Linux/Mac
  venv\Scripts\activate  # Windows
```

3. Instale as dependências:
```bash
  pip install -r requirements.txt
```

## 🚀 **Como Executar o Projeto**
1. Edite o arquivo `main.py` e insira suas credenciais:
```python
email = "seu-email@gmail.com"
senha = "sua-senha"
```
2. Execute o script:
```bash
  python main.py
```

## 📑 **Funcionalidades**
- Login automático no YouTube.
- Busca de vídeos para cada matéria.
- Criação de playlists organizadas.
- Adição automática de vídeos às playlists.

## 🚨 **Atenção**
- Para segurança, é recomendável usar autenticação de 2 fatores e gerar uma senha de aplicativo.
- Pode ser necessário ajustar os delays (`time.sleep`) para evitar bloqueios do YouTube.

## 🛡️ **Melhorias Futuras**
- Adicionar suporte a cookies para evitar login repetido.
- Tratar possíveis captchas durante o login.
- Melhorar a captura de vídeos para evitar vídeos duplicados.

## 👤 **Autor**
- [Seu Nome](https://github.com/seu-usuario)

📩 **Contribuições são bem-vindas!**
Sinta-se à vontade para abrir issues ou enviar pull requests. ✨

---
**PROJETO CRIADO PARA FINS EDUCACIONAIS!** 🎓

