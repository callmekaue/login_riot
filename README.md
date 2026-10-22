<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=D13639&height=230&section=header&text=RIOT%20LOGIN&fontSize=48&fontColor=FFFFFF&animation=fadeIn&fontAlignY=36&desc=Clone%20da%20tela%20de%20login%20%E2%80%94%20estudo%20Front-End&descAlignY=62&descSize=16" alt="Riot Login — clone da tela de login para estudo de Front-End">
</div>

<p align="center">
  <a href="https://www.riotgames.com/">
    <img src="https://img.shields.io/badge/Marca-Riot%20Games-D13639?style=for-the-badge&labelColor=1A1A1A" alt="Riot Games">
  </a>
  <a href="https://github.com/callmekaue/login_riot">
    <img src="https://img.shields.io/badge/Repositório-login_riot-FFFFFF?style=for-the-badge&labelColor=D13639&logo=github&logoColor=FFFFFF" alt="Repositório login_riot">
  </a>
  <a href="https://github.com/callmekaue">
    <img src="https://img.shields.io/badge/Autor-Kauê-1A1A1A?style=for-the-badge&labelColor=D13639" alt="Autor Kauê">
  </a>
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=FFFFFF&height=4" alt="">
<img src="https://capsule-render.vercel.app/api?type=rect&color=D13639&height=8" alt="">

<p align="center">
  <a href="#apresentacao">Apresentação</a> ·
  <a href="#demonstracao">Demonstração</a> ·
  <a href="#tecnologias">Tecnologias</a> ·
  <a href="#estrutura">Estrutura</a> ·
  <a href="#como-executar">Como executar</a> ·
  <a href="#objetivo">Objetivo</a> ·
  <a href="#funcionalidades">Funcionalidades</a> ·
  <a href="#aprendizados">Aprendizados</a> ·
  <a href="#proximos-passos">Melhorias futuras</a> ·
  <a href="#contribuicoes">Contribuições</a> ·
  <a href="#aviso">Aviso</a>
</p>

<h2 id="apresentacao">Apresentação</h2>

**Riot Games Login Clone** é uma recriação da tela de login da Riot Games, desenvolvida com HTML, CSS e JavaScript. O foco está na fidelidade visual, na responsividade e em práticas claras de Front-End.

O projeto não autentica em servidores da Riot e não substitui o cliente oficial. É um estudo de interface: layout, tipografia, campos de formulário, estados de botão e adaptação entre desktop e mobile.

<h2 id="demonstracao">Demonstração</h2>

A interface reproduz a experiência visual da página de login, com:

- composição moderna e responsiva
- layout inspirado no cliente oficial da Riot Games
- campos de autenticação estilizados
- adaptação para desktop e dispositivos móveis
- animações e efeitos visuais de apoio à interface

Para ver o resultado, abra `index.html` no navegador depois de clonar o repositório. Este README não depende de um arquivo local de preview. Se quiser uma captura na página do GitHub, adicione a imagem na raiz do projeto e referencie-a no Markdown.

<h2 id="tecnologias">Tecnologias</h2>

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js" alt="HTML, CSS e JavaScript">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-D13639?style=flat-square&logo=html5&logoColor=FFFFFF" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-FFFFFF?style=flat-square&logo=css3&logoColor=D13639" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-1A1A1A?style=flat-square&logo=javascript&logoColor=FFFFFF" alt="JavaScript">
  <img src="https://img.shields.io/badge/Flexbox-D13639?style=flat-square" alt="Flexbox">
  <img src="https://img.shields.io/badge/Media%20Queries-FFFFFF?style=flat-square&labelColor=D13639" alt="Media Queries">
</p>

| Tecnologia | Uso no projeto |
| --- | --- |
| HTML5 | Estrutura semântica da tela e do formulário |
| CSS3 | Visual, animações e identidade em vermelho e branco |
| JavaScript | Interação da interface e manipulação do DOM |
| Flexbox | Alinhamento do layout |
| Media Queries | Ajuste para diferentes larguras de tela |

<h2 id="estrutura">Estrutura do projeto</h2>

```text
login_riot/
├── index.html
├── style.css
├── script.js
├── assets/
│   ├── images/
│   └── icons/
└── README.md
```

Os arquivos principais ficam na raiz. Imagens e ícones, quando existirem, permanecem em `assets/`.

<h2 id="como-executar">Como executar</h2>

Não há etapa de build nem dependências de npm.

```bash
git clone https://github.com/callmekaue/login_riot.git
cd login_riot
```

Abra `index.html` no navegador, ou sirva a pasta com a extensão Live Server no Visual Studio Code / Cursor.

<h2 id="objetivo">Objetivo</h2>

Praticar, em um único recorte de interface real:

- estruturação de páginas web
- responsividade
- CSS avançado
- reprodução de interfaces existentes
- manipulação do DOM
- decisões de experiência do usuário

<h2 id="funcionalidades">Funcionalidades</h2>

O que a tela contempla neste estudo:

- campo de usuário
- campo de senha
- botão de login
- layout responsivo
- design inspirado na Riot Games

O envio do formulário não realiza login oficial. Não há autenticação real, recuperação de senha nem login social nesta versão.

<h2 id="aprendizados">Aprendizados</h2>

- HTML semântico
- CSS responsivo
- organização de arquivos Front-End
- práticas de UI e UX aplicadas a um formulário
- estruturação de componentes visuais

<h2 id="proximos-passos">Melhorias futuras</h2>

Itens em avaliação, ainda não apresentados como prontos:

- integração com API de autenticação
- tema claro e escuro
- validação de formulário
- fluxo de recuperação de senha
- login social (Google, Facebook, Apple)

Qualquer autenticação futura deveria ser apenas ilustrativa. Credenciais da Riot Games não devem ser coletadas por um clone de estudo.

<h2 id="contribuicoes">Contribuições</h2>

Sugestões de layout, acessibilidade e organização de código são bem-vindas.

```bash
git checkout -b minha-feature
git commit -m "Adiciona melhoria na interface"
git push origin minha-feature
```

Em seguida, abra um Pull Request no repositório.

<h2 id="autor">Autor</h2>

Desenvolvido por **Kauê**.

GitHub: [github.com/callmekaue](https://github.com/callmekaue)

<h2 id="aviso">Aviso</h2>

Este projeto existe apenas para fins educacionais e de estudo de Front-End.

Riot Games é marca registrada de Riot Games, Inc. Este repositório **não possui vínculo oficial** com a empresa, não é um cliente autorizado e não deve ser usado para coletar dados de login reais.

<img src="https://capsule-render.vercel.app/api?type=rect&color=D13639&height=6" alt="">

<p align="center">
  <strong>Riot Games Login Clone</strong><br>
  estudo de interface · HTML · CSS · JavaScript
</p>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=1A1A1A&height=140&section=footer&fontColor=FFFFFF&text=vermelho%20%C2%B7%20branco%20%C2%B7%20Front-End&fontSize=16&fontAlignY=70&animation=fadeIn" alt="vermelho, branco e Front-End">
</div>
