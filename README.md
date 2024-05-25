# Rinha do CPF

Desde que o mundo é mundo e os programadores resolveram virar pessoas, uma pergunta assola a humanidade: CPF é String ou é Int?

A partir dai surgiram dois grandes grupos. Do lado de lá existem os que defendem CPF como String, do lado de cá existe quem defenda CPF como INT. Um grupo declarou guerra ao outro grupo e assim vivemos em perfeito equilibrio.

## Ta, mas pq?

Na real que eu tava na internet e vi [esse post no twitter do Lucas Montano do canal Lucas Montano](https://x.com/lucas_montano/status/1794337467598069977), ai pensei: pô, legal, mas será que tem meio que como ir ainda além de String e Inteiro?

Vi uns posts de umas pessoas bem criativas:

- Augusto Galego: [CPF como binário](https://x.com/RealGalego/status/1794374829468193222)
- Danilo Assis: [CPF em várias colunas](https://x.com/daniloab_/status/1794353293218722009)

Entre outros. Ai pensei: tá, massa, mas acho que dá pra ser ainda mais criativo e engraçado e até aprender algo novo com isso, foi ai que decidi criar isso aqui.

## Qual é o objetivo?

O Desafio consiste em 2 trilhas:

- `Incrivel`: Aprendemos algo novo, algo que nunca foi pensado. Algo que vai mudar a forma como vemos o mundo. Nesse caso, conta a `Inovação`, `Criatividade` e `Aprendizado` (se contém algum conteúdo massa)
- `Engraçado`: Nesse caso é mais pela brincadeira, o que vale e conta muito é a criatividade. O objetivo nessa trilha conta a `Graça`, `Criatividade` e `Inovação` (se contém algum conteúdo massa)

- **Input**:

O objetivo é criar um programa que recebe um input de CPF. Esse input irá ocorrer em linha de comando

```bash
$ ./seu_programa input 123.456.789-10
$ <o_seu_output>
```

Seu programa é responsável por como é o output desse comando. Você pode me enviar uma URL/path, para QUALQUER output que NÃO SEJA string ou number, recomendo que você envie uma string apontando para o seu output.
Por exemplo: Se você quer salvar o CPF em uma imagem o output deveria ser algo como
`https://exemple.com/your_image.png` ou `C:/Users/your_user/your_image.png`

Se você salvar a imagem gerada localmente, garanta que ele funciona em qualquer computador, seja Mac/Linux/Windows, etc.

- **Output**:

O output deve nos mostrar o CPF inserido de alguma forma. Ele irá diferir dependendo da trilha escolhida:

### Incrivel

Para o output, você irá receber o output do comando `input` e você deve retornar o CPF

```bash
$ ./seu_programa output <o_seu_output>
$ 123.456.789-10
```

### Engraçado

Explique como o CPF irá aparecer no output, devemos jogar um joguinho? Ele é encodado de alguma forma? Preciso imprimir um papel em alguma impressora? Sei lá, seja criativo. Eu só quero que apareça, de alguma forma o número que foi salvo.

## Regras

- Você pode usar qualquer linguagem de programação
- Qualquer que seja a trilha escolhida, tem que ser direto ao ponto, sem muita enrolação. No máximo 5~10 minutos.
- Você deve ser capaz de salvar mais de um CPF ao mesmo tempo.
- Em ambas as trilhas você irá receber um ponto extra se pudermos pesquisar o CPF salvo. (usáriamos só os números para pesquisar). Por exemplo: pesquisar todos os CPFs que começam com 123
- Você pode usar qualquer biblioteca que quiser
- Não é obrigatório usar banco de dados
- Sei lá, só seja meio que criativo.

## Como enviar

- Só gerar uma issue com o link do seu Repo.
- Explique o que seu projeto faz e como ele funciona. É uma árvore? É um jogo? é um modelo pré-treinado que gera seu CPF? Sei lá, só me explica.

## Ideias

- Salvar o CPF em uma imagem
- Salvar o CPF em um arquivo 3d.
- Salvar em um gráfico de linha/pizza.
- Salvar em um arquivo de audio.
- Salvar o CPF em um arquivo de string, esse arquivo de string passa por um exec, o exec também valida o CPF.
- Salva em uma Blockchain
- Cria um modelo de IA, treina para que no output ele acerte o CPF salvo.
- Salvar em um banco de dados, onde você relaciona cada número do CPF a uma tabela diferente.
