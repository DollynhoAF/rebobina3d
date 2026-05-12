# Rebobina 3D

Landing page da Rebobina 3D — atelier de impressão 3D personalizada.

Site estático em HTML/CSS/JS puro, sem build step. Pronto pra deploy direto na Vercel.

## Stack

- HTML5 + Tailwind CSS (via CDN)
- GSAP + ScrollTrigger (animações de scroll)
- Lenis (smooth scroll)
- Vídeo em background (hero) e timeline de processo
- Fonte: Exo 2 + JetBrains Mono (Google Fonts)

## Rodar localmente

Como é um site estático, qualquer servidor HTTP serve. Exemplo:

```bash
# Python
python3 -m http.server 8000

# Node (com http-server)
npx http-server -p 8000

# Ou simplesmente abra o index.html no navegador
```

Acesse `http://localhost:8000`.

## Deploy na Vercel

1. Conecte o repositório na Vercel
2. Framework Preset: **Other** (ou deixe auto-detect)
3. Build Command: vazio
4. Output Directory: vazio (raiz)
5. Deploy

A Vercel serve o `index.html` direto da raiz. O `vercel.json` configura cache longo nos assets estáticos (vídeos, logos).

## Estrutura

```
.
├── index.html              # Página principal
├── assets/
│   ├── hero-bg.mp4         # Vídeo de fundo do hero
│   ├── printer-loop.mp4    # Vídeo da seção de processo
│   ├── logo.svg            # Logo (header)
│   └── logo-footer.png     # Logo (footer)
├── vercel.json             # Config de cache pra Vercel
└── DESIGN.md               # Design system docs
```
