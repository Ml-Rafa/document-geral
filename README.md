# Document-Geral

### Aqui coloco todo conteudo revisado que usei e uso durante meu estudo e trabalho em programação \n

<p> Vou começar falando um pouco sobre Orientação a objeto. </p>


Paradigmas são formas de reolver um problema da melhor forma.

existem alguns paradigmas e um deles é O.O ou Orientação voltada a objeto.

um exemplo de objeto é voce pensar num carro:
um carro tem varias caracteristicas como cor, marca, ano, modele etc.
o carro é um objeto e passamos essa visão para a linguagem computacinal, isso pra ficar mais facil mudar alguma caracteristicas se precisarmos.

e na programação passamos isso dessa forma , usando o exemplo do carro:


carro {
 cor: "Preta",
 marca: "Mercedes",
 ano: 1999,
 modelo: "M2c"
}

OBS: em javascrip eu acesso as propriedade desse objeto assim ...

carro.cor = "Preta"
carro.modelo = "M2c"

_____________________________________________

um exemplo que uso no meu dia de trabalho é :

ticket {
  id: 2,
  number: 1222,
  group_id: 1,
  title: "Ajuda"
}

OBS: em ruby eu acsso deferente de javascript , fica assim...

ticket[:group_id] = 1
ticket[:title] = "Ajuda"
