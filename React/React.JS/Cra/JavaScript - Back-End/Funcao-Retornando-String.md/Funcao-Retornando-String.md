Arquivo, App.js

Canal do youtube:

```js
https://www.youtube.com/engenheiroyoutuber
```

```js
//Importando o react
import React from "react";

const canal = () => {
  return "Engenheiro Youtuber";
};

export default function App_function_Component() {
  return (
    <div className="App_function_Component">
      <p> {"Canal: " + canal()} </p>
    </div>
  );
}
```
