# Feijoada da Rê — site

Landing page de uma página só, sem build e sem dependência de framework. Abre em qualquer celular.

**Feijoada da Rê** · Rua Paulo de Frontin, 70 — Cajuru, Curitiba/PR · 82940-070
Sábados, 11h às 14h · WhatsApp (41) 99138-6002 · Fone (41) 3532-4020


## No ar

**https://leonardobora.github.io/feijoada-da-re/**

Repositório: https://github.com/leonardobora/feijoada-da-re (público, GitHub Pages na branch `main`).

## Estrutura

```
index.html          a página inteira (HTML + CSS + JSON-LD)
assets/cartaz.jpg   cartaz da casa (usado na seção de encomenda)
.nojekyll           diz ao GitHub Pages para servir os arquivos como estão
```

## Publicar no GitHub Pages

1. Crie um repositório **público** (sugestão: `feijoada-da-re`).
2. Na pasta:

```bash
git init
git add .
git commit -m "site da Feijoada da Rê"
git branch -M main
git remote add origin git@github.com:SEUUSUARIO/feijoada-da-re.git
git push -u origin main
```

3. No repositório: **Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)` → Save**.
4. Em ~1 minuto o site fica em `https://SEUUSUARIO.github.io/feijoada-da-re/`.

### Dar acesso ao @mathelico

**Settings → Collaborators → Add people → `mathelico` → Write.** Ele recebe o convite por e-mail
e passa a poder editar o repositório. Se a ideia for só divulgar, o link da página basta.

### Depois de publicar

- Coloque o endereço final no JSON-LD (`index.html`, bloco `application/ld+json`): troque ou adicione
  `"url": "https://SEUUSUARIO.github.io/feijoada-da-re/"`. É o que o Google usa para ligar a página ao negócio.
- Cadastre essa URL no perfil do Google Maps da Feijoada da Rê (site), para o pino e a página apontarem um para o outro.

## O que ainda depende do dono

- **Formas de pagamento** — a página não afirma nenhuma. Se aceitarem Pix e dinheiro, vale escrever.
- **Raio de entrega** — hoje está "na região do Cajuru", sem bairros listados.
- **Fotos reais** — o único visual é o cartaz; duas ou três fotos da feijoada pronta aumentam conversão.
