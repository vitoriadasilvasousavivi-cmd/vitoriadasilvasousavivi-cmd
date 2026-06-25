````markdown
## 👩‍💻 Sobre Mim

```javascript
const vivi = {
  nome: "Vitória Sousa",
  apelido: "Vivi",
  localizacao: "Brasil 🇧🇷",
  area: "Front-End Developer",
  estudando: [
    "HTML",
    "CSS",
    "JavaScript",
    "Node.js"
  ],
  ferramentas: [
    "VS Code",
    "Canva",
    "Trello"
  ],
  objetivo: "Criar experiências digitais incríveis e evoluir como desenvolvedora."
}

Além disso, recomendo trocar a GIF do Pinterest por uma hospedada no GitHub ou Giphy, porque o Pinterest costuma bloquear carregamento externo e gerar falhas.

Também notei que você usou:

```html
<div align="center">
```

junto com blocos Markdown (`##`, `-`, ```javascript```). O GitHub às vezes não fecha corretamente as `<div>` e acaba renderizando tudo estranho.

Uma estrutura mais segura é:

```html
<h1 align="center">Seja Bem-Vinda ao meu perfil ❤️</h1>

<p align="center">
  <img src="SUA_GIF" width="250">
</p>

<p align="center">
  badges aqui
</p>
```

e depois continuar apenas com Markdown:

```markdown
---

## 👩‍💻 Sobre Mim

...

## 📊 Estatísticas

...
```
