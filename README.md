# Piedra-Papel-Tijera

```javascript
 /**
        * Compara dos valores (piedra-papel-tijera) para determinar que usuario ganó el juego.
        * 
        * @param  {string} choice1   valor piedra-papel-tijera del usuario 1
        * @param  {string} choice2   valor piedra-papel-tijera del usuario 2
        * @return  {string} result   mensaje con el usuario ganador
 */
      
  function compare(choice1, choice2) {
           
  let result = null;

  if (choice1 === choice2) {
                result = "Empate entre los jugadores";
  }

  if (choice1 === "piedra" && choice2 === "tijera") {
                result = "Gano usuario 1";
  }

  if (choice1 === "tijera" && choice2 === "papel") {
                result = "Gano usuario 1";
  }

  if (choice1 === "papel" && choice2 === "piedra") {
                result = "Gano usuario 1";
  }

  if (choice1 === "tijera" && choice2 === "piedra") {
                result = "Gano usuario 2";
  }

  if (choice1 === "papel" && choice2 === "tijera") {
                result = "Gano usuario 2";
  }

  if (choice1 === "piedra" && choice2 === "papel") {
                result = "Gano usuario 2";
  }

  return result;

  }
```
