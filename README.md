
# Quiz Naruto: quem fica no seu time?

Quiz em HTML puro (sem instalar nada). Dois personagens de Naruto entram em campo, você escolhe um e o outro é eliminado. O vencedor enfrenta o próximo até sobrar só um.

## Como jogar

1. Abra o `index.html` no navegador (duplo clique).
2. Clique em **Começar o quiz**.
3. Clique no personagem que você escolhe, ou use as teclas `1` / `2` (ou as setas ← →).
4. No fim, veja seu escolhido e a classificação completa.

## Estrutura

```
quiz-naruto/
├── index.html   # página, estilo e lógica em um único arquivo
└── README.md
```

## Publicar no GitHub

```bash
cd quiz-naruto
git init
git add .
git commit -m "Quiz Naruto: primeira versão"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/quiz-naruto.git
git push -u origin main
```

Antes disso, crie o repositório vazio `quiz-naruto` em github.com/new (sem README, sem .gitignore).

## Deixar online (GitHub Pages)

No repositório: **Settings → Pages → Branch: `main` / pasta `/ (root)` → Save**. O link fica em `https://SEU-USUARIO.github.io/quiz-naruto/`.

## Personalizar

Os personagens ficam na lista `PERSONAGENS` dentro do `index.html`. Para adicionar alguém, copie uma linha e mude nome, kanji, cor, vila e descrição.
