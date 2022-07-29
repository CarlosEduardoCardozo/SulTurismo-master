<template>
  <div class="primeiraParte">
    <div class="content">
      <div class="jpg">
        <img class="logosul" src="logoSulTurismo.jpeg" />
      </div>
      <div class="infoHeader">
        <div>
          <span>Quem somos?</span>
        </div>
        <div>
          <span>Contato</span>
        </div>
        <div>
          <span>Nossos Serviços</span>
        </div>
      </div>
    </div>
    <div class="info1">
      <div class="textInfo1">Somos especialistas em transporte escolar</div>
      <div>
        <hr />
      </div>
    </div>
  </div>
  <div class="linear"></div>
  <div class="segundaParte">
    <div class="leftSegundaParte">
      <div class="tituloSegundaParte">FRETAMENTOS DE ÔNIBUS</div>
      <div class="textoSegundaParte">
        A Sul turismo investe em tecnologia, adquirindo o que a de mais novo,
        seguro e sofisticado no ramo de transporte terrestre de passageiros
        proporcionando a você, familiares e amigos, uma viagem com o conforto e
        a segurança que merece.
      </div>
      <div class="segundotituloSegundaParte">MONTAMOS SUA VIAGEM</div>
      <div class="segundotextoSegundaParte">
        Você sabia que a style Sul turismo monta viagens personalizadas para
        grupos? Quer fazer aquela viagem em grupo? Montar aquela viagem da
        empresa para curtir um dia especial? Levar a família para conhecer um
        lugar novo? A Sul turismo, te ajuda a montar a sua viagem em grupo!
        Solicite um orçamento via whatsApp abaixo
      </div>
    </div>
    <div class="rightSegundaParte">
      <div class="form1">
        <img class="onibusum" src="src/imagens/onibus1.png" alt="" />
        <div class="form3">
          <img class="onibustres" src="src/imagens/onibus2.png" alt="" />
        </div>
      </div>
      <div class="form2">
        <img class="onibusdois" src="src/imagens/microonibus.png" alt="" />
      </div>
    </div>
  </div>
  <div class="parceira">
    <div class="tituloParceira">
      Somos empresa parceira do <br />
      Instituto Federal Catarinense
    </div>
  </div>
  <div class="terceiraParte">
    <div class="cotacao">
      Solicite uma <br />
      cotação <br />
      on-line.
    </div>
    <div class="formulario">
      <div class="tituloFormulario">Pedir um orçamento</div>
      <div class="subtituloFormulario">NOME:</div>
      <input class="inputs" type="text" />
      <div class="subtituloFormulario">CEP DE DESTINO:</div>
      <input class="inputs" type="text" />
      <div class="subtituloFormulario">CEP DE ORIGEM:</div>
      <input class="inputs" type="text" />
      <div class="subtituloFormulario">QUANTIDADE DE PESSOAS:</div>
      <input class="inputs" type="text" />
      <div class="subtituloFormulario">TELEFONE CONTATO:</div>
      <input class="inputs" type="text" />
      <div>
        <button class="enviar">ENVIAR</button>
      </div>
    </div>
  </div>
</template>
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Arimo:wght@600&display=swap");
head {
  margin: 0;
}

body {
  margin: 0px;
}
.primeiraParte {
  height: 800px;
  background-image: url("https://www.pousadadossonhos.com.br/wp-content/uploads/2019/12/308508-ponte-hercilio-luz-conheca-este-importante-ponto-de-florianopolis-1.jpg");
  z-index: 5;
  background-color: linear-gradient(
    180deg,
    rgba(0, 0, 0, 0.63) 0%,
    rgba(0, 0, 0, 0) 100%
  );
  opacity: 95%;
  border-radius: 25px;
}
.content {
  display: flex;
  align-items: center;
  background-color: rgb(0, 0, 0);
  height: 100px;
  border-radius: 15px;
  justify-content: space-between;
  padding: 0 10%;
}
.logosul {
  width: 75px;
}
.infoHeader {
  color: #ffff;
  justify-content: space-between;
  margin: 0 10% 0 0;
  text-transform: uppercase;
  display: flex;
  font-family: "Arimo";
  font-style: normal;
  font-weight: bold;
  font-size: 22px;
  line-height: 25px;
}
.infoHeader :hover {
  background-color: #fa943a;
  height: 100%;
  color: #703500;
}
.infoHeader span {
  padding: 15px;
}
.info1 {
  background: rgba(0, 0, 0, 0.72);
  border-radius: 30px;
  width: 713px;
  height: 308px;
  margin: 10% 0 0 25%;
}
.textInfo1 {
  font-family: "Arimo";
  font-style: normal;
  font-weight: 700;
  font-size: 45px;
  line-height: 57px;
  color: #ffffff;
  text-align: center;
  padding: 10% 0 0 0;
}
hr {
  border: 1px solid #f5a200;
  width: 373px;
  height: 0px;
  margin: 5% 0 0 25%;
}
.segundaParte {
  background-color: white;
  display: flex;
  height: 700px;
  margin: 0;
}
.leftSegundaParte {
  display: block;
  height: 450px;
  width: 600px;
  margin: 5% 10% 0 0;
}
.rightSegundaParte {
  display: flex;
}
.tituloSegundaParte {
  font-family: "Arimo";
  font-style: italic;
  font-weight: 700;
  font-size: 30px;
  line-height: 37px;
  color: #db6900;
  white-space: nowrap;
  padding: 1%;
  margin: 0 0% 0 10%;
}
.segundotituloSegundaParte {
  font-family: "Arimo";
  font-style: italic;
  font-weight: 700;
  font-size: 30px;
  line-height: 37px;
  color: #db6900;
  white-space: nowrap;
  padding: 2%;
  margin: 10% 0 0 28%;
}
.textoSegundaParte {
  font-family: "Arimo";
  font-style: italic;
  font-weight: 700;
  font-size: 20px;
  line-height: 23px;
  color: #000000;
  margin: 0 0% 0 10%;
}
.segundotextoSegundaParte {
  font-family: "Arimo";
  font-style: italic;
  font-weight: 700;
  font-size: 20px;
  line-height: 22px;
  color: #000000;
  margin: 0% 0 0 30%;
}
.primerosform {
  display: flex;
}
.form1 {
  background: rgba(255, 122, 0, 0.75);
  border-radius: 20px;
  width: 156px;
  height: 214px;
  margin: 20% 0 0 0;
}
.form2 {
  background: rgba(255, 122, 0, 0.75);
  border-radius: 20px;
  width: 208px;
  height: 192px;
  margin: 40% 0 0 40%;
}
.form3 {
  background: rgba(255, 122, 0, 0.75);
  border-radius: 20px;
  width: 156px;
  height: 287px;
  margin: 60% 0 0 0;
}
.onibusum {
  margin: 0 30% 0 0%;
}
.segundaParteImagens {
  display: flex;
}
.parceira {
  height: 300px;
  background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)),
    url("https://ifc.edu.br/wp-content/uploads/2018/12/foto-a%C3%A9rea-2.png");
}
.tituloParceira {
  font-family: "Arimo";
  font-style: italic;
  font-weight: 700;
  font-size: 36px;
  line-height: 41px;
  color: white;
  text-align: center;
  padding: 8% 0 0 0;
}
.terceiraParte {
  height: 1000px;
  display: flex;
}
.cotacao {
  font-family: "Arimo";
  font-style: normal;
  font-weight: 700;
  font-size: 45px;
  line-height: 60px;
  text-align: right;
  color: #000000;
  margin: 20% 0 0 10%;
}
.formulario {
  border-radius: 30px;
  width: 575px;
  height: 827px;
  box-sizing: border-box;
  border: 2px solid #c95c00;
  margin: 5% 0 0 20%;
}
.tituloFormulario {
  font-family: "Arimo";
  font-style: normal;
  font-weight: 700;
  font-size: 24px;
  line-height: 28px;
  color: #c95c00;
  margin: 15% 0 0 10%;
}
.subtituloFormulario {
  font-family: "Arimo";
  font-style: normal;
  font-weight: 700;
  font-size: 18px;
  line-height: 21px;
  color: #c95c00;
  margin: 10% 0 0 10%;
  padding: 3px;
}
.inputs {
  margin: 1% 0 0 10%;
  padding: 3px;
  border-style: none none solid none;
  width: 425px;
  border-color: #ffad68;
}
.enviar {
  border-radius: 5px;
  height: 50px;
  width: 150px;
  border-color: #c95c00;
  margin: 10% 0 0 35%;
  background: #ffad68;
  font-family: "Arimo";
  font-style: normal;
  font-weight: 700;
  font-size: 20px;
  color: black;
}
</style>
