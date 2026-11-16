# Conferência Flechas 2027

Landing page da Conferência Flechas 2027 (tema: Reino), Igreja Batista do Bacacheri, Curitiba.

Site estático: `index.html` sem build, com as fontes (Maison des Pastel e Helvena) em `/fonts`, o Lenis em `/js` e as imagens em `/img`.

`/fonts`, `/js` e `/img` são servidos com cache de 1 ano (`immutable`, veja `vercel.json`): ao trocar um desses arquivos, **troque também o nome** (ex.: `castelo-invertido-2.svg`) e atualize a referência no `index.html`, senão quem já visitou continua vendo a versão antiga.

## Publicar na Vercel
1. Em vercel.com, **Add New → Project** e importe este repositório.
2. Framework Preset: **Other**. Build Command e Output Directory: deixe em branco.
3. **Deploy**. Cada push na branch `main` publica de novo automaticamente.

## Antes de publicar
- Trocar `#inscricao` nos botões de ingresso pelo link oficial de inscrição.
- Definir o valor do Day Pass (hoje "Em breve").
- Confirmar programação e preletores.
