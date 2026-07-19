# DDG — Site de inscrições

Site estático para o Campeonato DDG de Esportes Eletrônicos.

## Arquivos

- `index.html`: página principal e formulário;
- `regulamento.html`: regulamento-base;
- `sucesso.html`: página exibida após o envio;
- `css/style.css`: identidade visual;
- `js/script.js`: menu, contador e máscara de WhatsApp.

## Como visualizar

Abra o arquivo `index.html` no navegador.

## Como ativar o formulário

1. Crie uma conta gratuita no Formspree.
2. Crie um novo formulário.
3. Copie o endpoint fornecido.
4. No arquivo `index.html`, procure:

```html
action="https://formspree.io/f/SEU_CODIGO"
```

5. Substitua `SEU_CODIGO` pelo código verdadeiro.

## Como alterar a data do campeonato

No arquivo `index.html`, procure:

```html
data-date="2026-12-15T20:00:00-03:00"
```

Substitua pela data e pelo horário corretos.

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie todos os arquivos deste projeto.
3. Abra `Settings`.
4. Entre em `Pages`.
5. Em `Build and deployment`, selecione `Deploy from a branch`.
6. Escolha a branch `main` e a pasta `/root`.
7. Salve.

O endereço ficará parecido com:

```text
https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/
```

## Pontos que ainda precisam ser definidos

- data oficial;
- modalidades;
- formato das partidas;
- premiação;
- idade mínima;
- região permitida;
- contato oficial;
- redes sociais;
- regulamento definitivo;
- política de privacidade;
- existência ou não de taxa de inscrição.

## Observação

O regulamento incluído é apenas um modelo inicial e deve ser revisado antes da publicação.
