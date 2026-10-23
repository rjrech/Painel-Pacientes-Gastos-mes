# Painel de pacientes por categoria e especialidade

Site estático para acompanhar, mês a mês, primeiras consultas, retornos e total de pacientes entre dezembro de 2025 e setembro de 2026.

## Recursos

- Seletor de categoria e especialidade.
- Três gráficos mensais: primeiras consultas, retornos e total.
- Indicadores rápidos de volume da categoria, volume da especialidade e mês de maior movimento.
- Ranking das 10 especialidades com maior volume no período dentro da categoria selecionada; clicar em um item atualiza os gráficos.
- Fonoaudiologia Adulto e Fonoaudiologia Infantil aparecem uma única vez, com os registros dos nomes com e sem “(10 sessões)” reunidos.
- Meses/valores sem registro permanecem sem ponto e não são convertidos em zero.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie `index.html` para a raiz do repositório.
3. Acesse **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/(root)`, e salve.
5. Aguarde o GitHub disponibilizar o endereço público da página.

O site funciona como arquivo estático e não exige servidor, instalação ou bibliotecas externas.
