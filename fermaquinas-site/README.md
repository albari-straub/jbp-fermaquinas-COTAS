# Plano de Parceria Fermaquinas 2027

Landing comercial do JBP 2027 da Fermaquinas. Pagina estatica, sem build e sem
dependencia: e um `index.html` autocontido mais a pasta `assets/`.

## Publicar no GitHub Pages

1. Crie um repositorio e envie **o conteudo desta pasta na raiz** (o `index.html`
   precisa ficar na raiz do repositorio, nao dentro de uma subpasta).
2. No repositorio: **Settings > Pages**.
3. Em *Source*, escolha **Deploy from a branch**.
4. Selecione a branch (`main`) e a pasta **/ (root)**. Salve.
5. Em cerca de um minuto o site sai no ar em
   `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

Pelo terminal:

```
git init
git add .
git commit -m "Landing JBP Fermaquinas 2027"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git
git push -u origin main
```

## O que tem aqui

| Arquivo | O que e |
|---|---|
| `index.html` | A pagina inteira: HTML, CSS e JavaScript no mesmo arquivo |
| `assets/` | Fotos do projeto executivo, logo, favicon e o video do tour |
| `.nojekyll` | Impede o GitHub Pages de processar a pasta com Jekyll |

O video (`assets/video_lp.mp4`, cerca de 11 MB) e carregado por streaming nativo,
entao a pagina abre antes de ele terminar de baixar. Esta bem abaixo do limite de
100 MB por arquivo do GitHub.

## Dominio proprio

Para usar um dominio da Fermaquinas, crie um arquivo chamado `CNAME` na raiz com
o dominio dentro (exemplo: `plano.fermaquinas.com.br`) e aponte o DNS para o
GitHub Pages. O caminho fica em Settings > Pages > Custom domain.

## Trocar fotos

As imagens ficam em `assets/`. Para trocar qualquer uma, substitua o arquivo
mantendo o mesmo nome. Todas sao 16:9 para nao cortar nem sobrar nos cards.

## Observacoes

- A secao do gerador de contrato esta desativada nesta versao.
- A ferramenta interna de troca de fotos nao aparece no site publicado.
- Os botoes de reserva abrem o e-mail em `thiago@askn.com.br`.