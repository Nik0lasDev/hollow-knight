<!--
  Ruínas do Crepúsculo · README
  Projeto experimental de ação e plataforma em HTML5 Canvas.
-->

<div align="center">

# ☾ Ruínas do Crepúsculo

### Um pequeno jogo de ação e plataforma em um mundo de ruínas.

**Explore. Ataque. Esquive. Sobreviva.**

<p>
  <img alt="Status do projeto" src="https://img.shields.io/badge/status-prot%C3%B3tipo-8fbfd0?style=for-the-badge">
  <img alt="Tecnologia" src="https://img.shields.io/badge/feito_com-HTML5_%2B_JavaScript-e7cda0?style=for-the-badge">
  <img alt="Plataforma" src="https://img.shields.io/badge/plataforma-navegador-9baed0?style=for-the-badge">
  <img alt="Idioma" src="https://img.shields.io/badge/idioma-pt--BR-c7a6df?style=for-the-badge">
</p>

[**▶ JOGAR AGORA**](https://nik0lasdev.github.io/hollow-knight/) · [Ver código-fonte](./blob/main/index.html) · [Reportar um problema](../../issues)

</div>

---

## ✦ Sobre o projeto

**Ruínas do Crepúsculo** é um protótipo 2D de ação e plataforma inspirado no ritmo de combate dos metroidvanias, incluindo *Hollow Knight*. A ideia é construir uma base jogável para, aos poucos, adicionar novas mecânicas, inimigos, áreas e desafios.

O projeto usa **HTML5 Canvas e JavaScript puro**: não precisa de bibliotecas externas, instalação de dependências ou processo de build.

> [!NOTE]
> Este projeto está em desenvolvimento. Os gráficos e sistemas atuais são uma base inicial, não a versão final do jogo.

## ⚔️ Recursos atuais

- **Combate corpo a corpo** — golpe direcional, alcance definido, recarga e reação dos inimigos.
- **Sistema de vida** — cinco pontos de vida, dano, invulnerabilidade temporária e tela de derrota.
- **Movimentação de plataforma** — caminhada, pulo, gravidade e plataformas.
- **Esquiva rápida** — dash para atravessar o cenário com mais agilidade.
- **Três tipos de inimigos** — rastejante, saltador e brutamontes, cada um com resistência e comportamento próprios.
- **Essência** — recurso recebido ao derrotar inimigos.
- **Cenário com rolagem lateral** — câmera acompanha o personagem por uma área de jogo extensa.
- **Controles para toque** — botões na tela para jogar em dispositivos móveis.

## 🎮 Controles

| Ação | Teclado / computador | Celular |
|:--|:--|:--|
| Mover | `A` / `D` ou setas | Botões ← / → |
| Pular | `Espaço`, `W` ou ↑ | **PULAR** |
| Atacar | `J`, `Z` ou clique esquerdo | **GOLPE** |
| Esquivar | `Shift` ou `K` | **DASH** |

## 🚀 Entrar no jogo

Use o botão **▶ JOGAR AGORA** no topo para abrir a versão jogável no navegador. Se o endereço ainda não abrir, é necessário ativar a publicação do GitHub Pages uma única vez:

1. Abra **Settings → Pages** neste repositório.
2. Em **Build and deployment**, escolha **Deploy from a branch**.
3. Selecione a branch `main` e a pasta `/ (root)` e clique em **Save**.
4. Aguarde a publicação e acesse [nik0lasdev.github.io/hollow-knight](https://nik0lasdev.github.io/hollow-knight/).

Depois da publicação, o botão do README leva diretamente ao jogo — não à página do código.

### Executar localmente

1. Faça o download ou clone este repositório.
2. Abra o arquivo `index.html` em um navegador moderno.
3. Clique em **Entrar nas ruínas** e comece a jogar.

### Alternativa — usar um servidor local

Se preferir executar por um servidor HTTP, abra o terminal na pasta do projeto e rode:

```bash
python -m http.server 8000
```

Depois, acesse [http://localhost:8000](http://localhost:8000).

## 🗂️ Estrutura

```text
hollow-knight/
├── index.html   # jogo, estilos, desenho e lógica
└── README.md   # documentação do projeto
```

## 🧭 Próximos passos

- [ ] Melhorar os sprites e as animações de combate.
- [ ] Criar novas áreas conectadas e pontos de descanso.
- [ ] Adicionar chefes e padrões de ataque mais variados.
- [ ] Implementar habilidades desbloqueáveis e progressão.
- [ ] Salvar progresso e configurações.
- [ ] Melhorar efeitos sonoros, música e feedback de impacto.
- [ ] Testar e ajustar a jogabilidade em diferentes tamanhos de tela.

## 🛠️ Tecnologias

| Tecnologia | Uso |
|:--|:--|
| HTML5 | Estrutura da página |
| CSS | Interface responsiva e controles |
| JavaScript | Física, combate, inimigos e estado do jogo |
| Canvas 2D | Renderização do cenário e personagens |

## 🤝 Contribuição

Sugestões, relatos de bugs e melhorias são bem-vindos. Ao reportar um problema, informe os passos para reproduzi-lo, o navegador utilizado e se estava jogando no computador ou no celular.

## 📄 Licença

Nenhuma licença foi definida neste momento. Consulte o responsável pelo projeto antes de reutilizar ou redistribuir o código.

---

<div align="center">

Feito para evoluir, um golpe de cada vez. ☾

</div>
