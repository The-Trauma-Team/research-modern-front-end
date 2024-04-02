[← voltar](https://github.com/grupoboticario/stargate/tree/main#prismic-headless-cms)

# ​ Prismic

<img src="https://img.shields.io/badge/PORTAIS%20VD-STARGATE-%236F42B6.svg?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNjcuNTQgMzQwLjQ0Ij48ZGVmcz48c3R5bGU+LmNscy0xe2ZpbGw6I2ZiNmIwNDt9LmNscy0xLC5jbHMtMntmaWxsLXJ1bGU6ZXZlbm9kZDt9LmNscy0ye2ZpbGw6IzA0YWNlYzt9PC9zdHlsZT48L2RlZnM+PGcgaWQ9IkNhbWFkYV8yIiBkYXRhLW5hbWU9IkNhbWFkYSAyIj48ZyBpZD0ic3ZnIj48ZyBpZD0ic3ZnZyI+PHBhdGggaWQ9InBhdGgwIiBjbGFzcz0iY2xzLTEiIGQ9Ik0xMTIuMDgsMzEuMDcsMTEyLDYyLjEzLDEwNy4zMiw1OWMtOS45NS02LjY0LTguMjctNy4zMy00MS4xNiwxNi44Ny0yLDEuNDQtNi4xNSw0LjUyLTkuMzUsNi44NGwtOCw1Ljg4Yy0xLjIzLjkxLTQsMi45NC02LjE2LDQuNTEtNC4yNSwzLjA5LTYuNjgsNS41OS04LjA2LDguMjktMy40NSw2Ljc2LDIuNTgsMTUuMjUsMTAuODksMTUuMzEsNCwwLDQuMzgtLjE3LDE0LjIyLTcuNCwxNi41Mi0xMi4xNSwzMy41Ni0yNC42MSwzNC0yNC44N3MyLDEsMTIsOS42M2w2LjUxLDUuNjRWMTI3bC01LjM4LDUuNTJjLTcuNDgsNy42NS0yOS4wNiwyOS44MS0zMC42MywzMS40My0uNy43NC02LjY2LDYuODUtMTMuMjMsMTMuNThzLTEyLDEyLjM5LTEyLjA3LDEyLjU3Yy0uNCwxLTEuNzUtLjY1LTcuNi05LjUxLTIxLjQzLTMyLjQzLTE5LjE0LTI5LjUtMjQuMi0zMUMxMC40OCwxNDcsLjcyLDE1My4wNi4xMywxNjEuMzhjLS4yMywzLjE5LTEuNjIuNDcsMTQuMzQsMjhDMjEuOTQsMjAyLjIsMjYsMjA5LjI3LDMxLjYyLDIxOC45M2M2LjQ4LDExLjIyLDExLjUzLDE0Ljk1LDE5LjA4LDE0LDYuMjctLjc0LDcuNDktMS43LDI2LjA3LTIwLjQ0QzkyLjIsMTk3LDkzLDE5Ni4xOCw5My41NSwxOTYuODhjLjI5LjQsNC42MSw2LjM0LDkuNTgsMTMuMjFsOSwxMi40N3Y1OC41NWwtNC4xMyw0TDk2LjgxLDI5Ni4wNWMtOC43OCw4LjUyLTkuNDUsOS42Mi05LjQ1LDE1LjUzczIuMzUsOS42MSw3LjYxLDEyLjE5YzYsMywxMCwyLjcsMTQuNjMtMWwyLjM5LTEuOTEuMSw5Ljc4LjEsOS43OGgxMi40OFYwSDExMi4xOGwtLjEsMzEuMDciLz48cGF0aCBpZD0icGF0aDEiIGNsYXNzPSJjbHMtMiIgZD0iTTE0MiwxNzAuMjJWMzQwLjQ0aDEyLjVWMzE1LjI2TDE3NC42MSwyOTVjMjEuNC0yMS41LDIxLjQxLTIxLjUsMjIuMTctMjUuODIsMS4wOS02LjE4LjMxLTcuNjYtMTYuMjMtMzEtNy41NC0xMC42Mi0xNC44MS0yMC44OC0xNi4xNi0yMi44bC02LjItOC44Yy0zLjA5LTQuNC0zLjc0LTUuNTQtMy43NC02LjY2LDAtMS42LS4yNy0xLjIzLDguMjMtMTEuMTksNy4yMy04LjQ4LDcuNjktOSwyMC4yOC0yMy45QzE5NCwxNTEuODEsMTk3Ljg5LDE0Ny4zNiwxOTgsMTQ3LjVhMzIuMjgsMzIuMjgsMCwwLDEsLjU0LDMuMjQsNTQuNzEsNTQuNzEsMCwwLDAsMS4xMSw1LjY5YzEuMTIsNC4yNCwyLjQxLDkuMTUsNC4zOSwxNi44LDMuMzgsMTMuMDUsMy45LDEzLjc4LDE3LjMxLDIzLjkybDE5LDE0LjQxYzkuMzcsNy4xLDEwLjYsNy45MiwxMi40NSw4LjMxYTEyLjI1LDEyLjI1LDAsMCwwLDE0LjYxLTEyLjE1Yy4wNy01LjYyLDItMy42Ny0yMi4yMS0yMi4xNS0xOC43NS0xNC4zMS0xOC43My0xNC4zLTE5LjA5LTE1LjY3LS42Ny0yLjU2LTguNDUtMzMtMTAtMzktLjg1LTMuMzMtMS42NC02LjI2LTEuNzctNi40OS0uMy0uNTQtNC4yNC0zLjU4LTI3LjgxLTIxLjQ1bC0yMi40Mi0xNy02LjUzLTUtMy4yMi0yLjQ0VjBIMTQyVjE3MC4yMk0yMDYuMjgsMzYuNTlhMzQuNiwzNC42LDAsMCwwLTI1LjksNDljMTMuODcsMjkuMjgsNTYuNjQsMjUuMTEsNjQuODUtNi4zMyw2LjIyLTIzLjgxLTE0LjQ4LTQ2LjQ5LTM4Ljk1LTQyLjY3bS01MC41MywyMjEsNi44LDguODItMi4xNiwyLTYuNjQsNi4yNWMtMi40OCwyLjMzLTQuNzQsNC4zNi01LDQuNTItLjQ1LjI2LS41My0xLjkyLS41My0xNS4xOSwwLTEwLjQ3LjEzLTE1LjQ1LjM4LTE1LjM3czMuNDQsNC4xLDcuMTcsOSIvPjwvZz48L2c+PC9nPjwvc3ZnPg==" />

<img src="images/prismic/prismic.svg" align="right" alt="Prismic Logo" width="150" height="150" />

- [Sobre o Prismic](#sobre-o-prismic)
- [Modelagem de conteúdo](#modelagem-de-conteudo)
  - [Workflow](#workflow)
  - [Custom Types & Documents](#custom-types-documents)
  - [Custom Types](#custom-types)
  - [Documents](#documents)
  - [Slices](#slices)

**Stargate: Prismic - Docs**<br />
&emsp;[📄 &nbsp; Stargate - Headless CMS Bechmark: Por que escolhemos o Prismic?](https://github.com/grupoboticario/stargate/tree/main/docs/prismic-headless-benchmark.md)<br />
&emsp;[📄 &nbsp; Stargate: Prismic Documents](https://github.com/grupoboticario/stargate/tree/main/docs/prismic-stargate-documents.md)

---

## Sobre o Prismic <a name="sobre-o-prismic"></a>
O **Prismic** é o <a href="https://en.wikipedia.org/wiki/Headless_content_management_system" target="_blank">Headless CMS 🔗</a> utilizado pelos portais de venda direta gerados a partir do 👾 &nbsp; **Stargate** e que tem o objetivo de servir um repositório de conteúdo, disponibilizando os dados através de requisições em uma api `RESTFul/GraphQl` para exibição de conteúdo em múltiplos dispositivos. 👉 &nbsp; [Documentação oficial](https://prismic.io/docs)

<img src="images/prismic/headless-cms.jpg" alt="Como funciona um headless cms" width="600">

---

## Modelagem de conteúdo <a name="modelagem-de-conteudo"></a>
> O Content model `(Modelo de conteúdo)` define a estrutura de todo o conteúdo de um website ou app.
De forma similar à modelagem de um banco de dados, o processo de estruturar o conteúdo é chamado de `content modeling / modelagem de conteúdo`.

<img src="images/prismic/content-modeling.jpg" alt="Content Modeling" width="600">

---

### Workflow <a name="workflow"></a>
> O Workflow abaixo é apenas uma sugestão a partir de um fluxo linear e pode variar entre projetos, uma vez que algumas etapas podem ocorrer simultâneamente ou em casos em que o conteúdo é criado nas fases iniciais do projeto:

1. `Especificações do projeto`
2. `Arquitetura de informação`
3. `Sketches/Wireframes`
4. 👉 &nbsp; `Modelagem de conteúdo`
5. `Criação de Conteúdo`
6. `Desenvolvimento Front-end`

> ⚠️ &nbsp; Independente do workflow utilizado, a modelagem de conteúdo só deve ser feita quando você já sabe como será a estrutura visual do conteúdo. Caso contrário, o `modelo de conteúdo` pode se tornar irrelevante, o que levaria a

- muitos hacks ou inconveniências no front-end, ou
- refação do modelo de conteúdo e trabalho extra aos responsáveis pela criação e gerencimaneto do conteúdo.

--- 

### Custom types & Documents <a name="custom-types-documents"></a>
> O Prismic possui dois recursos principais para modelagem e criação de conteúdo: `Documents` e `Custom types`.
> Resumidamente, desenvolvedores serão responsáveis pela modelagem de conteúdo através de `Custom Types` enquanto criadores e gerentes de conteúdo são responsáveis pela criação, edição, publicação e revisão de `Documents`.

*Tela de modelagem de conteúdo:*

<img src="images/prismic/content-builder.jpg" alt="Custom types editor" width="100%">

---

### 🎨 ​&nbsp; Custom types <a name="custom-types"></a>
> Custom Types são `modelos/templates`, onde é organizada a estrutura dos `Documents`, contendo campos como *Title Page*, *UID* e também os *slices* que serão utilizados. Os Custom types podem ser utilizados de duas maneiras:

#### **Repeatable**
> É possível criar diversos Documents a partir desse custom type. Exemplo: `Page`

#### **Single**
> Apenas um Document pode utilizar esse custom type. Exemplo: `Login`

<img src="images/prismic/content-type.jpg" alt="Content Type: Example" width="600">

---

### 📄 &nbsp; Documents <a name="documents"></a>

> `Documents` são arquivos que usam templates/modelos a partir de `Custom types`, onde é possível criar e editar todos os conteúdos que serão exibidos aos nossos clientes. As áreas de edição podem mudar de acordo com o template utilizado.

<img src="images/prismic/content-editor.jpg" alt="Content Type: Example" width="100%">

### 🧩 &nbsp; Slices <a name="slices"></a>
> `Slices` são componentes dinâmicos disponíveis a partir de uma `Slice Zone`, permitindo que editores de conteúdo componham layouts de página mais ricos e com mais liberdade.

<img src="images/prismic/slices-bg.gif" alt="Content Type: Example" width="600">
