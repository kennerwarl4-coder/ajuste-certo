# Ajuste Certo

Página de vendas da apostila **Ajuste Certo**: guia ilustrado de consertos e ajustes em roupa pronta para geração de renda extra na máquina de costura doméstica (Sequência M.A.C.: Medir, Alfinetar, Costurar).

## Estrutura

```
index.html                  página completa (HTML, CSS e JS num arquivo só)
assets/logo-ajuste-certo-giz.png
assets/fotos/               imagens otimizadas usadas pela página (WebP)
assets/fotos/PROMPTS-FOTOS.md  prompts e nomes de arquivo de cada imagem
criativos-kit/              peças soltas para criativos de anúncio
```

## Antes de publicar

No fim do `index.html`, preencha o bloco `CONFIG`:

- `checkout`: link do checkout (vazio = os botões só rolam até o preço)
- `EXPERT.experiencia` e `EXPERT.formacao`: só dados reais e verificáveis
- `DEPOIMENTOS`: só depoimentos reais, com autorização

Para ver os espaços de imagem vazios, abra a página com `?slots` no fim do endereço.

## Publicar

É um site estático: funciona em GitHub Pages, Netlify, Vercel ou qualquer hospedagem de arquivos.
No GitHub Pages: Settings → Pages → Branch `main` / pasta raiz.
