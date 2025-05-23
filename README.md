
<div align="center">
<h1>🖼️ ASCII Live Menu</h1>

![Python](https://img.shields.io/badge/Python-3.11+-blue?style=for-the-badge&logo=python)
![Status](https://img.shields.io/badge/status-active-success?style=for-the-badge)
![Platform](https://img.shields.io/badge/platform-cross--platform-lightgrey?style=for-the-badge)

</div>

## 📜 Descrição

**ASCII Live Menu** é um pequeno utilitário em Python que permite navegar por uma galeria interativa de artes animadas ASCII diretamente no terminal, utilizando a API pública do [ascii.live](http://ascii.live). 

Com um menu simples e visual, você pode exibir animações como Batman, Parrot, Rickroll, Nyan Cat e muito mais com apenas alguns cliques.

## 🧰 Funcionalidades

- Menu interativo no terminal
- Animações ASCII diretamente da internet via `curl`
- Suporte para Linux, macOS e Windows
- Fácil de expandir com novas artes

## 📦 Instalação

Você pode instalar via **pip** (recomendado após publicação no PyPI):

```bash
pip install ascii-live-menu
```

Ou clone o repositório:

```bash
git clone https://github.com/KelvenVS/ASCII_Live_Menu.git
cd ascii-live-menu
python main.py
```

> **Requisitos:** Python 3.1+

## ▶️ Como Usar

Após rodar o script, será exibido um menu numerado com todas as opções disponíveis. Basta digitar o número correspondente para ver a arte em ASCII.

```bash
python -m ascii_live_menu.main
```

Caso tenha instalado pelo Pypi
```bash
ascii_menu
```

**Algumas opções disponíveis:**
- `batman`
- `rick`
- `donut`
- `playstation`
- `nyan`
- `torus-knot`
- ...e muitos outros!

### Interromper
Pressione `Ctrl+C` a qualquer momento para encerrar a execução.

## 🛠️ Desenvolvimento

Adicione facilmente novas artes ao menu:

```python
self.menu_dict["nome-da-arte"] = lambda: get_ascii("nome-da-arte")
```

Veja mais artes disponíveis em: [http://ascii.live](http://ascii.live)

## 🧪 Exemplo de Execução

```plaintext
############################################################### Menu ###############################################################
1. batman
2. can-you-hear-me
3. hes
4. knot
...
Escolha uma das opções: 1
```

## 📄 Licença

Este projeto está licenciado sob os termos da **MIT License**. Veja o arquivo `LICENSE` para mais detalhes.

## 👨‍💻 Autor

Desenvolvido por [KelvenVS](https://github.com/KelvenVS) com foco em aprendizado e diversão com terminal e ASCII art.

## Agradecimentos

Este projeto é uma adaptação educacional baseada na incrível iniciativa do repositório original [ascii-live](https://github.com/hugomd/ascii-live) desenvolvido por [@hugomd](https://github.com/hugomd).  
Todo o crédito pelas artes e comandos `curl` vai para esse projeto. Esta ferramenta em Python foi criada apenas como uma forma divertida e educativa de acessar esses conteúdos de forma interativa no terminal.
