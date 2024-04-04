# HTML

*Hypertext*
*Markup*
- TAG h1 (negrito)
- TAF A gerador de LINK

table (tabela)
thead (cabeçalho)
tr (cada uma das linhas)
th (texto do cabeçalho)
width="100%" (largura)
tbody (corpo da tabela)
Td corpo escrito da tabela
strong (negrito)
br (quebra de linha)
small (letra menor)
 ajustar texto no cabecalho (<thead style="text-align: left">)


*Language*


# CSS


/* Cascading StyleSheet*/

```css
/* declarações */
body, table, input, button {
  font: 300 16px/140% 'Roboto', sans-serif;
}

body {
  background-color: #121214;
  color: #ffffff;
}

table {
   padding: 32px;
   border: 1px solid red;
   margin: 32px;
}




# Javascript


OBJETO DO JAVASCRIPT  = {}

array = []


```js
// variaveis
const mensagem = "Oi tudo bem?"
// tipos de dados
  //number
  //string
// funcao
alert(mensagem)
``

LISTA 

// objeto javascript
const participante = {
  nome: "Filipe Marquez",
  email: "filipe@gmail.com",
  dataInsricao: new Date(2024, 2, 22, 19, 00),
  dataCheckIn: new Date(2024, 2, 25, 22, 00)
}

// array
let participantes = [
  {
    nome: "Filipe Marquez",
    email: "filipe@gmail.com",
    dataInsricao: new Date(2024, 2, 22, 19, 00),
    dataCheckIn: new Date(2024, 2, 25, 22, 00)
  },
]

// estrutura d repetição - loop
  for (let participante of participantes) {
    output = output + criarNovoParticipante(participante)
  }


  // condicional
  if(participante.dataCheckIn == null) {
   dataCheckIn = `
   <button
     data-email="${participante.email}"
     onclick="fazerCheckIn(event)"
   >
   Confirmar check-in
   </button>
   `
  }
  