# store

Páginas públicas de suporte e de privacidade das apps (publicadas com GitHub Pages: https://etrag.github.io/store/).

- `apostoque/` — Aposto que… (`index.html` = suporte, `privacy.html` = política de privacidade)
- `atina/` — Atina (antes Kcal): `index.html` = suporte, `privacy.html` = política de privacidade, ambas geradas com `node scripts/gen-store-pages.cjs <pasta>` do repositório etrag/kcal (a política sai de `kcal-frontend/src/content/privacy.tsx`); tem o seu próprio `style.css`
- `kcal/` — redireciona para `atina/` (os URLs antigos, usados na App Store e no AdMob, continuam a funcionar)
- Uma pasta por app; cada app usa `../style.css`. Atualizar a política **antes** de sair uma versão que trate mais dados.
