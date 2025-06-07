# .zsh - Configuração ZSH modular por @luizomf

Este repositório contém meu setup completo de ZSH, totalmente modularizado.
Criei esse esquema anos atrás e, honestamente, fiquei surpreso comigo mesmo quando redescobri, então agora está de volta, repaginado e funcional.

---

## Como usar

Adicione isso ao seu `~/.zshrc`:

```zsh
source "${HOME}/.zsh/use_this_to_load"
````

Isso vai carregar automaticamente todos os arquivos da pasta `.zsh`.

---

## 📁 Estrutura dos arquivos

* `aliases`: comandos úteis para Git, Docker, pip, macOS cleanup, ffmpeg e mais
* `config`: otimizações de histórico e comportamento do ZSH
* `exports`: variáveis de ambiente e PATH (pyenv, nvm, openssl, etc)
* `functions`: funções personalizadas (como `componentTs`, `aula_c`, `addtocspell`, etc)
* `keybinds`: binds extras, como opção+seta para navegar palavras
* `use_this_to_load`: script que orquestra o carregamento modular com verificação de arquivos

---

## Curiosidade

Esse setup nasceu por necessidade e preguiça de usar frameworks gigantes como Oh My Zsh ou Prezto.
Hoje em dia, virou um pequeno legado pessoal. Modular, limpo e fácil de versionar.

Se você quiser um setup leve, personalizável e fácil de entender: use isso como base.
Se quebrar tudo, a culpa é sua. Se funcionar lindamente, fui eu que fiz 😎

---

## License

MIT (só me dá um star se curtir).

👨‍🚀 Criado por Luiz Otávio Miranda — [@luizomf](https://github.com/luizomf)

---
