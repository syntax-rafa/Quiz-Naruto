[README (1).md](https://github.com/user-attachments/files/34833927/README.1.md)
# Quiz Naruto: quem fica no seu time?

Quiz de duelos com personagens de Naruto, feito em HTML, CSS e JavaScript puros. Dois personagens entram em campo, você escolhe um e o outro é eliminado. O escolhido enfrenta o próximo da fila, até sobrar apenas um.

**Jogue online:** https://syntax-rafa.github.io/Quiz-Naruto/

## Como jogar

1. Clique em **Começar o quiz**.
2. Escolha um dos dois personagens em campo (clique na carta, use as teclas `1` e `2` ou as setas ← →).
3. O personagem não escolhido é eliminado e outro entra no lugar dele.
4. Repita até restar um só. No final você vê o seu escolhido e a classificação completa.
5. Clique em **Jogar de novo** para recomeçar com uma nova ordem.

## Regras

- Só 2 personagens ficam em campo por vez.
- Quem você escolhe continua; quem você não escolhe está fora para sempre.
- São 16 personagens e 15 duelos por partida.
- A ordem é sorteada a cada partida, então o resultado pode mudar.

## Personagens

Naruto, Sasuke, Sakura, Kakashi, Hinata, Gaara, Rock Lee, Itachi, Jiraiya, Tsunade, Shikamaru, Neji, Minato, Tenten, Ino e Temari.

## Tecnologias

- HTML5
- CSS3 (layout responsivo, funciona no celular)
- JavaScript puro, sem bibliotecas e sem instalação

## Estrutura do projeto

```
Quiz-Naruto/
├── index.html   # página, estilo e lógica em um único arquivo
└── README.md
```

## Rodar no seu computador

```bash
git clone https://github.com/syntax-rafa/Quiz-Naruto.git
cd Quiz-Naruto
```

Depois, abra o `index.html` no navegador (duplo clique). Não precisa de servidor nem de instalação.

## Publicar no GitHub Pages

1. No repositório, vá em **Settings → Pages**.
2. Em **Branch**, escolha `main` e a pasta `/ (root)`.
3. Clique em **Save**. Em alguns minutos o site fica no ar no endereço acima.

## Personalizar

Os personagens ficam na lista `PERSONAGENS` dentro do `index.html`. Para adicionar alguém, copie uma linha e altere nome, kanji, cor, vila e descrição.

## Autor

Feito por [syntax-rafa](https://github.com/syntax-rafa).

Naruto é uma obra de Masashi Kishimoto. Este é um projeto de fã, sem fins comerciais.
