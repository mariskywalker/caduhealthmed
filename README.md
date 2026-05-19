# CADU Health — Apresentação Institucional

Landing page institucional (HTML estático) para o ecossistema CADU / operadoras de saúde.

## Abrir localmente

```bash
python3 -m http.server 8766
```

- http://localhost:8766/
- http://localhost:8766/cadu-unimed-bh.html

## Deploy

| Plataforma | URL |
|------------|-----|
| **Vercel** (raiz do projeto) | `https://seu-projeto.vercel.app/` |
| **GitHub Pages** | `https://mariskywalker.github.io/caduhealthmed/` |

O arquivo **`index.html`** na raiz evita erro `404 NOT_FOUND` ao acessar a URL sem nome de arquivo.

### GitHub Pages

1. Repositório → **Settings** → **Pages**
2. **Build and deployment** → Source: **Deploy from a branch**
3. Branch: **main** / pasta **/ (root)**
4. Salve e aguarde 1–2 min; acesse `https://mariskywalker.github.io/caduhealthmed/`

### Vercel

Conecte o repositório; não é necessário framework. A raiz já contém `index.html`.

## Estrutura

- `index.html` — mesma página que `cadu-unimed-bh.html` (entrada para hosting)
- `cadu-unimed-bh.html` — alias legado
- `assets/` — imagens dos fundadores e ícones
