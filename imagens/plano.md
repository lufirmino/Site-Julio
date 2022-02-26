Header
Logo Táxi do Júlio

inputs menu

Inicio
como funciona
contato
--------------------

Hero section
imagem de pessoas chamando o taxi
opacidade
O melhor taxi online de viçosa H2
A mais de 20 anos servindo a população viçosense com excelência.

Botões como funciona /chame o julio

Caixa de agendamento
30% box background color amarelo
Em cima desta faixa imagen de táxi

Título
Chame o julio
Abas (duas)
uma pra agendar
outra agora

*Agora
cep origem*
cep destino*
nome*
telefone*
email(opcional)

*Agendar

cep origem*
cep destino*
nome*
telefone*
email(opcional)
data
horario
 
 
Botão para solicitar

Tarifa da cidade de Viçosa

Silvestre x Centro              R$----
João Brás x Centro              R$----
Santo Antônio x Centro          R$----
Liberdade x Centro              R$----
Tiradentes x Centro             R$----
Belvedere x Centro              R$----
Ramos x Centro                  R$----
Santa Clara x Centro            R$----
Lourdes x Centro                R$----
Fátima x Centro                 R$----
Estrelas x Centro               R$----
Bom Jesus x Centro              R$----
Nova Viçosa x Centro            R$----
São José do Triunfo x Centro    R$----
Barrinha x Centro               R$----
Sagrada Família                 R$----

como funciona

Insira os detalhes da viagem
Agende sua viagem antecipadamente
Dia da viagem
Forma de pagamento

Contato

Imagem moças chamando táxi
Liga para o Julio
31996634571
mebuscajulio@taxidojulio.com
Dísponivel 24 horas por dia

Botao chame o julio

Rodapé

logo preto e branco
solicitar chamada

imagem taxi
<a href='https://www.freepik.com/vectors/car'>Car vector created by upklyak - www.freepik.com</a>

-------------------------------
HTML
<section class="agendamento">
        <div class="lado-agendar"><img src=80 alt="Taxi"></div>
        <div class="agendar-conteudo">
          <h2>Chame o Júlio</h2>
          <div class="opcoes">
            <a class="op--link" href="#">Agora</a>
            <a class="op--link" href="#">Agendar</a>
          
          </div>
          <div class= "agendamento--agora">
            <div class="input">
              <label for="cep-origem-1">Cep de Origem</label>
              <input id="cep-origem-1" type="number" placeholder="Cep de Origem" required></div>
            <div class="input">
              <label for="cep-destino-1">Cep de Destino</label>
              <input id="cep-destino-1" type="number" placeholder="Cep de Destino" required ></div>
            <div class="input">
              <label for="nome">Nome</label>
              <input  id="nome" type="text" placeholder="Nome" required></div>
            <div class="input">
              <label for="email">Email</label>
              <input  id="email" type="email" placeholder="Email"></div>
            <div class="input">
              <label for="telefone">Telefone</label>
              <input id="telefone" type="number" placeholder="Telefone" required></div>
            <input type="submit">
          </div>
          <div class= "agendamento--depois">
            <div class="input">
              <label for="cep-origem-1">Cep de Origem</label>
              <input id="cep-origem-1" type="number" placeholder="Cep de Origem" required></div>
            <div class="input">
              <label for="cep-destino-1">Cep de Destino</label>
              <input id="cep-destino-1" type="number" placeholder="Cep de Destino" required ></div>
            <div class="input">
              <label for="nome">Nome</label>
              <input  id="nome" type="text" placeholder="Nome" required></div>
            <div class="input">
              <label for="email">Email</label>
              <input  id="email" type="email" placeholder="Email"></div>
            <div class="input">
              <label for="telefone">Telefone</label>
              <input id="telefone" type="number" placeholder="Telefone" required></div>
            <div class="input">
              <label for="datetime">Data e Hora</label>
              <input id="datetime" type="datetime" name="Data e Horário" id="datetime" required></div>
            <input type="submit">
          </div>
        </div>
      </section>
      ------------------------
      CSS
      
.agendamento{
max-width: 80rem;
background-color: var(--cor6);
margin: -5rem auto 0 auto;
display: flex;
padding: 1rem;
box-shadow: 0px 0px 15px 5px rgba(0, 0, 0, 0.1);
border-radius: 0.5rem;


}

.agendamento--depois{
display: none;

}

.agendamento--agora{
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1rem;


}
.lado-agendar{
  width: 30%;
  background-color: var(--cor3);
  position: relative;
  
}
.lado-agendar img{
  width: 45rem;
  position:absolute;
  top: 15%;
  left: -25%;

}
.agendar-conteudo{
  padding-left: 13rem;
  padding-top:3rem ;
  display: flex;
  flex-direction: column;
  gap: 1.5rem;
 
 
  

}
.agendar-conteudo h2{
font-size: 3rem;
}
.opcoes{
  display: flex;
  gap: 3rem;
}
.op--link{
  text-decoration: none;
  color: #646464;
  text-transform: uppercase;
  font-weight: 700;
  font-size: 1.4rem;
}
.input input{
border: none;
outline: none;
padding: 1rem;
border-radius: 1rem;
border-bottom: 2px solid rgba(251, 197, 0,0);
font-family: inherit;

}
.input input:focus{
  border-bottom: 2px solid rgba(251, 197, 0,0.5);
 
}
.input{
  display: flex;
  flex-direction: column;
  font-size: 1.4rem;
  color: #474747;


}
---------------------------


<form class="agen-agora">
            <div class="input-field">
              <input class="input" type="text" name="Cep de Origem" placeholder="Cep de origem">
              <input class="input"    type="text" name="Cep de destino" placeholder="Cep de destino">
              <input class="input" type="text" name="nome" placeholder="Nome">
              <input class="input" type="tel" name="telefone" placeholder="Telefone">
              <input type="number" name="numero" placeholder="Passageiros">
              <input class="input" type="email" name="email" placeholder="Email">
              <input  class="input" type="submit" name="enviar" placeholder="Enviar">
            </form>
---------------------------



.botao-f{
  background-color: var(--cor6);
  color: var(--cor7);
  height:4rem ;
  width: 30rem;
  margin: auto;
}

