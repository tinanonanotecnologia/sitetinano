# Tinano · site

Site estático (um único `index.html`), sem build.

## Publicar na Vercel
1. Crie um repositório no GitHub e envie esta pasta.
2. Na Vercel: Add New → Project → importe o repositório → Framework: **Other** → Deploy.
3. Domínio: Settings → Domains → adicione `tinano.com.br` e `www.tinano.com.br` e aponte o DNS no Registro.br conforme a Vercel indicar.

## Editar
- Contatos, textos e FAQ: direto no `index.html`.
- Cores: variáveis no topo do `<style>` (`--navy`, `--cyan`, `--coral`…).
- Bibliotecas via CDN: Three.js r128, GSAP 3.12.5 + ScrollTrigger, Lenis 1.1.13.
