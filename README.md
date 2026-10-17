# patriciasousasilva.com

Portefólio pessoal de Patrícia Sousa Silva, estudante de Engenharia Informática na Universidade Aberta.

Página estática em HTML e CSS, publicada na Cloudflare (Workers com ficheiros estáticos).

## Estrutura

```
public/
  index.html        conteúdo da página
  styles.css        estilos (cores, tipografia, layout)
  favicon.svg       ícone do separador
  og-patricia.png  imagem mostrada quando o link é partilhado
  img/              capturas dos projetos
wrangler.jsonc      configuração de publicação na Cloudflare
```

## Ver localmente

Abrir `public/index.html` no browser.

## Publicar

Cada `git push` para o ramo `main` publica automaticamente a nova versão.
