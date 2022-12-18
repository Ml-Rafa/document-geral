# Document-Geral

### Aqui coloco todo conteudo revisado que usei e uso durante meu estudo e trabalho em programação \n

<p> Vou começar falando um pouco sobre Orientação a objeto. </p>


Paradigmas são formas de reolver um problema da melhor forma.

existem alguns paradigmas e um deles é O.O ou Orientação voltada a objeto.


Os 4 pilares da orientação a objeto é:
* Abstração 
* Encapsulamento
* Herança
* Polimorfismo

Abstração :
Identidade
atributos
métodos

Encapsulamento:
se refere a esconder propriedades ou métodos do objeto, por seguraça por exemplo.

Herança :
se refere ao compartirar ou reuso codigo entre outras classes por exemplo.

Polimorfismo:
referenciar um objeto de algumas formas diferentes.

entramos entao no conceito de classe.

uma class é como uma forma ou gabarito onde vamos criar nosso objeto.
ficando assim sua estrutura.

classe objeto atributos e ações



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

_____________________________________________
_____________________________________________
Como funciona a web ?
_____________________________________________
_____________________________________________

Arquitetura basica web

### Cliente :

Dispositivos por onde temos acesso as informações, como celular e computador conectados a uma internet.

### Servidor

Onde ficar armazenado os dados que seram acessados pelo cliente.

_____________________________________________

# Comunicação na web

Para nos comunicarmos na internet, precisamos saber qual o IP e  a porta que queremos acessar,
resumindo para acessar um site, digitamos a URL https://www.site.com,

Quando digitamos num navegador uma URL , o navegador se encarrega de saber qual é o IP e a porta
que estamos tentando acessar.
