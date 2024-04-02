[← voltar](https://github.com/grupoboticario/stargate/tree/main#prismic-headless-cms)

# ​ Prismic

<img src="https://img.shields.io/badge/PORTAIS%20VD-STARGATE-%236F42B6.svg?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNjcuNTQgMzQwLjQ0Ij48ZGVmcz48c3R5bGU+LmNscy0xe2ZpbGw6I2ZiNmIwNDt9LmNscy0xLC5jbHMtMntmaWxsLXJ1bGU6ZXZlbm9kZDt9LmNscy0ye2ZpbGw6IzA0YWNlYzt9PC9zdHlsZT48L2RlZnM+PGcgaWQ9IkNhbWFkYV8yIiBkYXRhLW5hbWU9IkNhbWFkYSAyIj48ZyBpZD0ic3ZnIj48ZyBpZD0ic3ZnZyI+PHBhdGggaWQ9InBhdGgwIiBjbGFzcz0iY2xzLTEiIGQ9Ik0xMTIuMDgsMzEuMDcsMTEyLDYyLjEzLDEwNy4zMiw1OWMtOS45NS02LjY0LTguMjctNy4zMy00MS4xNiwxNi44Ny0yLDEuNDQtNi4xNSw0LjUyLTkuMzUsNi44NGwtOCw1Ljg4Yy0xLjIzLjkxLTQsMi45NC02LjE2LDQuNTEtNC4yNSwzLjA5LTYuNjgsNS41OS04LjA2LDguMjktMy40NSw2Ljc2LDIuNTgsMTUuMjUsMTAuODksMTUuMzEsNCwwLDQuMzgtLjE3LDE0LjIyLTcuNCwxNi41Mi0xMi4xNSwzMy41Ni0yNC42MSwzNC0yNC44N3MyLDEsMTIsOS42M2w2LjUxLDUuNjRWMTI3bC01LjM4LDUuNTJjLTcuNDgsNy42NS0yOS4wNiwyOS44MS0zMC42MywzMS40My0uNy43NC02LjY2LDYuODUtMTMuMjMsMTMuNThzLTEyLDEyLjM5LTEyLjA3LDEyLjU3Yy0uNCwxLTEuNzUtLjY1LTcuNi05LjUxLTIxLjQzLTMyLjQzLTE5LjE0LTI5LjUtMjQuMi0zMUMxMC40OCwxNDcsLjcyLDE1My4wNi4xMywxNjEuMzhjLS4yMywzLjE5LTEuNjIuNDcsMTQuMzQsMjhDMjEuOTQsMjAyLjIsMjYsMjA5LjI3LDMxLjYyLDIxOC45M2M2LjQ4LDExLjIyLDExLjUzLDE0Ljk1LDE5LjA4LDE0LDYuMjctLjc0LDcuNDktMS43LDI2LjA3LTIwLjQ0QzkyLjIsMTk3LDkzLDE5Ni4xOCw5My41NSwxOTYuODhjLjI5LjQsNC42MSw2LjM0LDkuNTgsMTMuMjFsOSwxMi40N3Y1OC41NWwtNC4xMyw0TDk2LjgxLDI5Ni4wNWMtOC43OCw4LjUyLTkuNDUsOS42Mi05LjQ1LDE1LjUzczIuMzUsOS42MSw3LjYxLDEyLjE5YzYsMywxMCwyLjcsMTQuNjMtMWwyLjM5LTEuOTEuMSw5Ljc4LjEsOS43OGgxMi40OFYwSDExMi4xOGwtLjEsMzEuMDciLz48cGF0aCBpZD0icGF0aDEiIGNsYXNzPSJjbHMtMiIgZD0iTTE0MiwxNzAuMjJWMzQwLjQ0aDEyLjVWMzE1LjI2TDE3NC42MSwyOTVjMjEuNC0yMS41LDIxLjQxLTIxLjUsMjIuMTctMjUuODIsMS4wOS02LjE4LjMxLTcuNjYtMTYuMjMtMzEtNy41NC0xMC42Mi0xNC44MS0yMC44OC0xNi4xNi0yMi44bC02LjItOC44Yy0zLjA5LTQuNC0zLjc0LTUuNTQtMy43NC02LjY2LDAtMS42LS4yNy0xLjIzLDguMjMtMTEuMTksNy4yMy04LjQ4LDcuNjktOSwyMC4yOC0yMy45QzE5NCwxNTEuODEsMTk3Ljg5LDE0Ny4zNiwxOTgsMTQ3LjVhMzIuMjgsMzIuMjgsMCwwLDEsLjU0LDMuMjQsNTQuNzEsNTQuNzEsMCwwLDAsMS4xMSw1LjY5YzEuMTIsNC4yNCwyLjQxLDkuMTUsNC4zOSwxNi44LDMuMzgsMTMuMDUsMy45LDEzLjc4LDE3LjMxLDIzLjkybDE5LDE0LjQxYzkuMzcsNy4xLDEwLjYsNy45MiwxMi40NSw4LjMxYTEyLjI1LDEyLjI1LDAsMCwwLDE0LjYxLTEyLjE1Yy4wNy01LjYyLDItMy42Ny0yMi4yMS0yMi4xNS0xOC43NS0xNC4zMS0xOC43My0xNC4zLTE5LjA5LTE1LjY3LS42Ny0yLjU2LTguNDUtMzMtMTAtMzktLjg1LTMuMzMtMS42NC02LjI2LTEuNzctNi40OS0uMy0uNTQtNC4yNC0zLjU4LTI3LjgxLTIxLjQ1bC0yMi40Mi0xNy02LjUzLTUtMy4yMi0yLjQ0VjBIMTQyVjE3MC4yMk0yMDYuMjgsMzYuNTlhMzQuNiwzNC42LDAsMCwwLTI1LjksNDljMTMuODcsMjkuMjgsNTYuNjQsMjUuMTEsNjQuODUtNi4zMyw2LjIyLTIzLjgxLTE0LjQ4LTQ2LjQ5LTM4Ljk1LTQyLjY3bS01MC41MywyMjEsNi44LDguODItMi4xNiwyLTYuNjQsNi4yNWMtMi40OCwyLjMzLTQuNzQsNC4zNi01LDQuNTItLjQ1LjI2LS41My0xLjkyLS41My0xNS4xOSwwLTEwLjQ3LjEzLTE1LjQ1LjM4LTE1LjM3czMuNDQsNC4xLDcuMTcsOSIvPjwvZz48L2c+PC9nPjwvc3ZnPg==" />

<img src="images/prismic/prismic.svg" align="right" alt="Prismic Logo" width="150" height="150" />

- [Headless CMS Benchmark: Por que escolhemos o Prismic?](#benchmark)
  - [Fase I: Análise de abordagens disponíveis](#abordagens)
  - [Fase I: Conclusões](#conclusoes-abordagens)
  - [Fase II: Benchmark entre Headless CMS](#headless-benchmark)
  - [Fase II: Conclusões](#headless-conclusoes)

**Stargate: Prismic - Documentação Relacionada:**
&emsp; [📄 &nbsp; Prismic: Content Modeling](https://github.com/grupoboticario/stargate/tree/main/docs/prismic.md)<br />
&emsp; [📄 &nbsp; Stargate: Prismic Documents](https://github.com/grupoboticario/stargate/tree/main/docs/prismic-stargate-documents.md)

---

## Headless CMS Benchmark: Por que escolhemos o Prismic? <a name="benchmark"></a>
> O *Prismic* foi escolhido por apresentar a melhor pontuação no benchmark realizado pela equipe de [portais de venda direta](https://github.com/orgs/grupoboticario/teams/squad-portais), faseado em duas etapas:

1. Consideração das `abordagens disponíveis` e pontuação a partir dos critérios de avaliação considerados relevantes para a `experiência dos desenvolvedores`, `equipe de conteúdo` e para o `negócio`.
2. Definida a abordagem na primeira fase, mapear e comparar as principais ferramentas disponíveis no mercado.


*Critérios de pontuação:*

<img src="images/prismic/bechmarch-convention.jpg" alt="Mapa de Convenções" width="600">


### Fase I: Análise de abordagens disponíveis <a name="abordagens"></a>
> Foram consideradas as seguintes abordagens possíveis: `Extender o Admin CMS`, `Desenvolver um CMS do Zero`, `CMS Full Stack` e `Headless CMS`.

<img src="images/prismic/bechmarch-aproach.jpg" alt="Abordagens Disponíveis">

### Fase I: Conclusões <a name="conclusoes-abordagens"></a>

<img src="images/prismic/bechmarch-aproach-conclusion.jpg" alt="Abordagens">

---

### Fase II: Benchmark entre Headless CMS <a name="headless-benchmark"></a>
> Definida a estratégia de seguir por uma solução de Headless CMS, conduzimos o benchmark comparando as principais ferramentas de mercado: `WordPress`, `Strapi`, `Contentful` e `Prismic`.

<img src="images/prismic/bechmarch-headless-table.jpg" alt="Convenções">

### Fase II: Conclusões <a name="headless-conclusoes"></a>

<img src="images/prismic/bechmarch-headless-conclusion.jpg" alt="Convenções">