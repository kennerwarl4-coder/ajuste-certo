# Ajuste Certo

Página de vendas do **Ajuste Certo**: método completo para abrir um negócio de consertos e ajustes em roupa pronta na máquina de costura doméstica (Especialização nos 18 consertos mais lucrativos + Sequência M.A.C. + Kit de Aceleração com Instagram, WhatsApp e Divulgação Silenciosa para faturar de R$ 4.300 a R$ 6.700/mês).

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
