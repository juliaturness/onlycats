# Projeto 2 - Gerenciamento de Membros e Pagamentos

## Avaliação da Apresentação

### Notas

* Apresentação: 9/10
* Perguntas: 5/10

### Perguntas

1. Explique como importar os dados de um arquivo JSON.
* **Resposta**: Existem diferentes maneiras de importar um arquivo JSON no JavaScript, dependendo do ambiente (navegador ou Node.js). A abordagem mais comum para carregar um JSON no navegador é usar a função `fetch()`, que realiza uma requisição HTTP assíncrona.

  - Exemplo:
```js
fetch('./dados.json')
  .then(response => response.json()) // Converte a resposta para JSON
  .then(dados => {
    console.log(dados.nome); 
  })
  .catch(error => console.error("Erro ao carregar JSON:", error));
```

  - Vantagens:
    + Funciona em qualquer navegador moderno.
    + Pode buscar JSON de APIs remotas.
    + Não precisa do `assert { type: 'json' }`.

2. Explique o que cada parte da função `proper()` no arquivo `utils.js:151` faz.
* **Resposta**: A função recebe uma string e capitaliza a primeira letra de cada palavra, deixando o restante das letras em minúsculas. Esse estilo é conhecido como "Title Case" (capitalização de título).  

```js
function proper(str) {
    return str
        .split(' ')  
        .map(word => word.charAt(0).toUpperCase() + word.slice(1).toLowerCase())  
        .join(' ');
}
```
  * `split(' ')` divide a string em um **array de palavras**, separando pelos espaços.
  * `.map(word => ...)` percorre cada palavra do array e aplica uma transformação nela.
  * `word.charAt(0).toUpperCase()` pega a primeira letra da palavra e converte para maiúscula.
  * `word.slice(1).toLowerCase()` pega o restante da palavra (a partir do segundo caractere) e converte para minúsculas.  
  * Concatenação (`+`) junta a primeira letra em maiúscula com o restante da palavra em minúsculas.
  * `.join(' ')` reagrupa o array de palavras transformadas em uma única string, separando por espaços.  