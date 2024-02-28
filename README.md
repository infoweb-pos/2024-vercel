# Notas de aula - HTML e JS (em construção)

## Informações gerais
- **Objetivo**: publicar HTML + CSS como aplicativo web (_application hosting_)
- **Público alvo**: alunos da disciplina de POS (Programação Orientada a Serviços) do curso de Infoweb (Técnico Integrado em Informática para Internet) no CNAT-IFRN (Instituto Federal de Educação, Ciência e Tecnologia do Rio Grande do Norte - Campus Natal-Central)
- **Professor**: [L A Minora](https://github.com/leonardo-minora/)

## Pré-requisitos
1. Conta ativa no Github (todos nossos projetos serão via github)
2. Criar conta no [vercel](vercel.com)

## Tarefas
1. Fork desse respositório para sua conta github. Assim posso acompanhar quem esta fazendo.
2. Criar o arquivo index.html, [conforme arquivo abaixo](https://github.com/infoweb-pos/2024-vercel/blob/main/README.md#arquivo-indexhtml), na pasta principal do repositório.
3. Abrir vercel e autenticar
4. Criar novo projeto no vercel e conectar ao seu repositório do github

## Links
- [MDN Mozilla Developer Network](https://developer.mozilla.org/pt-BR/)
  - [HTML: Linguagem de Marcação de Hipertexto](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- Hosting de aplicações web
  - [vercel](https://vercel.com/)
  - [heroku](https://www.heroku.com/)
  - [netify](https://www.netlify.com/)
  - [render](https://render.com/)

## Arquivo index.html

```html
<html>
  <head>
    <title>Infoweb 2024 - Tarefas</title>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  </head>
  <body>
    <div>
      <div>
        <h1>Lista de tarefas</h1>
      </div>
      <div>
        <input type="text" placeholder="informe a tarefa" />
        <button>Adicionar</button>
      </div>
      <ul>
        <li>
          <div>
            <input type="checkbox" name="tarefa_1" id="tarefa_1" />
            <label for="tarefa_1">
              <span>Front-end web</span>
              <span>Construir um front-end sem estilo</span>
            </label>
          </div>
        </li>
        <li>
          <div>
            <input type="checkbox" name="tarefa_1" id="tarefa_1" />
            <label for="tarefa_1">
              <span>Montar estilo do Front-end web</span>
              <span>Usar framewerk CSS para estilizar o front-end</span>
            </label>
          </div>
        </li>
      </ul>
    </div>
  </body>
</html>

```
