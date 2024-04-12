#javascript
//array
let participantes [
  nome: "Lucas Hoffmann",
  email: "lucashoffs123@gmail.com",
  dataInscricao: new Date(2024, 9, 30, 20, 07),
  dataCheckin: new Date(2024, 9, 30, 20, 10)
]


//estrutura de repetição - loop
for(let participante of participantes) {
  output = output + criarNovoParticipante(participante)
  //faça alguma coisa aqui
  //enquanto estiver participantes nesta lista
}
