<h3 align="center">
  Github Explorer
</h3>

<blockquote align="center">"Filho, se você parar de aprender, logo esquecerá o que sabe." Provérbios 19:27 NTLH.</blockquote>

<img alt="GoStack" src="./assets/github-explorer.gif" />


## :rocket: Sobre a aplicação

Na aplicação temos duas páginas:

**1) Dashboard** Exibe a lista de repositórios cadastrados.

**2) Repository** Os detalhes do repositório com as seguintes informações:

```js
{
    full_name: string;
    description: string;
    stargazers_count: number;
    forks_count: number;
    open_issues_count: number;
    owner: {
        login: string;
        avatar_url: string;
    }
}
```

A aplicação busca na API do github o repositório informado e armazena no localStorage.

### Aplicado os conceitos:

* **`TypeScript`**

* **`Axios`**

* **`Styled-Components`**

* **`LocalStorage`**


Aplicação desenvolvida no nível 3 do GoStack da Rocketseat!
