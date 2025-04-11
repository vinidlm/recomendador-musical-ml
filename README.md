# 🎵 Spotify Track Info & Visualization

Este projeto realiza a autenticação com a API do Spotify utilizando o fluxo de credenciais de cliente (Client Credentials Flow) para buscar informações públicas de faixas e exibir a imagem da capa do álbum com matplotlib.

---

## 📦 Funcionalidades

- Busca informações de uma música a partir do `track_id` ou nome (via DataFrame).
- Consulta a API do Spotify usando a biblioteca `Spotipy`.
- Exibe a imagem do álbum com `matplotlib` e `scikit-image`.
- Variáveis sensíveis são mantidas em um arquivo `.env` seguro.

---

## 🛠️ Tecnologias utilizadas

- [Python](https://www.python.org/)
- [Spotipy](https://spotipy.readthedocs.io/)
- [Matplotlib](https://matplotlib.org/)
- [scikit-image](https://scikit-image.org/)
- [python-dotenv](https://pypi.org/project/python-dotenv/)

---

🧠 Observações:
  - Este projeto utiliza apenas dados públicos da API do Spotify.

  - Não requer login do usuário ou permissões especiais.

  - Ideal para análise de dados musicais, dashboards ou projetos de visualização.
