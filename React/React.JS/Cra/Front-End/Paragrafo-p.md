Canal do youtube:

```js
https://www.youtube.com/engenheiroyoutuber
```

## Parágrafo

<p> </p>

### React.Js

React.js, temos que importar o React, para que possa funcionar o Jsx dentro do
componente. Exemplo abaixo:

```js
import React from "react";
```

React.js, tempos o "Div" dentro da div fica o Jsx.

```js
<div>
  Aqui vai conter o JSX, vamos ver mas para frente como vai ficar este lugar
  aqui.
</div>
```

React.Js, temos o "p", ele é o parágrafo do seu texto.

```js
<h1>Titulo</h1> //Titulo
<p>Parágrafo<p/> //Paragrafo
```

React.js - Arquivo, "App.js" Neste exemplo abaixo, utilizamos o
styled-components, para isso você deve instalar a biblioteca, utilizando o
comando abaixo: Lembrando, não vou entrar em, detalhes aqui, pois na outra
pasta, que citei acima, é o requesito para fazer este exemplo aqui, instalar o
yarn, agora se for instalar com o npm, não precisa instalar o yarn.

```js
yarn add styled-components
ou
npm install --save styled-components
```

```js
import React from "react"; // importando o React
import styled from "styled-components"; // Importando o styled components

{
  /*Estilizando CSS*/
}
const Geral = styled.div`
  background-color: black;
  h1 {
    color: white;
  }
  p1 {
    color: blue;
  }
`;

//Componente Function Componente
function App() {
  return (
    <Geral>
      {/*Aqui dentro JSX, ja está funcionando agora, porque importamos o react*/}
      <h1>Titulo</h1>
      <p1>Parágrafo</p1>
    </Geral>
  );
}

export default App; // Exportando o componente, para que você possa reutilizar ele depois em outros lugares, o nome deste componente é App
```
