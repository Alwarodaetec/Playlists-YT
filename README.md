# 🎯 YouTube Playlist Bot

Este projeto é um script automatizado com Selenium para criar playlists no YouTube com vídeo-aulas organizadas por matéria de vestibular! 🚀

## 🛠️ **Tecnologias Utilizadas**
- Python
- Selenium
- WebDriver Manager

## 🚀 **Como Executar o Projeto**
1. Edite o arquivo `simplicacaoYT.py` e insira suas credenciais:
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

---
**PROJETO CRIADO PARA FINS EDUCACIONAIS!** 🎓

