<template>
  <Header />
  <section class="showcase">
    <h1>DESENVOLVIMENTO DE SITES E APLICATIVOS</h1>
    <h2>Somos uma agência de desenvolvimento e marketing digital.</h2>
    <h3>Precisa de um site para seu negócio?</h3>
    <button>SOLICITE UM ORÇAMENTO</button>
  </section>

  <section class="servicos">
    <h1 class="servicos">Nossos Serviços</h1>
    <div class="container-flex">
      <div class="left">
        <img
          src="@/assets/home-page/servicos/web-dev.png"
          alt="Desenvolvimento Web"
          srcset=""
        />
        <p>Desenvolvimento Web</p>
        <img
          src="@/assets/home-page/servicos/app-design.png"
          alt="Desenvolvimento Web"
          srcset=""
        />
        <p>Design de Aplicativos</p>
        <img
          src="@/assets/home-page/servicos/hosting.png"
          alt="Desenvolvimento Web"
          srcset=""
        />
        <p>Hospedagem de Sites e Bancos de Dados</p>
      </div>

      <div class="right">
        <div>
          <h2>Design Responsivo</h2>
          <p>
            A necessidade de acessar informações rapidamente e em movimento
            agora é a norma. Você pode deslumbrar seus visitantes fornecendo a
            melhor experiência.
          </p>
        </div>
        <div>
          <h2>Arquitetura</h2>
          <p>
            Uma estrutura de página lógica e fácil de navegar ajuda seus
            usuários e os mecanismos de busca a encontrarem o que estão
            procurando.
          </p>
        </div>
        <div>
          <h2>Manutenção</h2>
          <p>
            Nossa equipe de design e desenvolvimento web utiliza práticas de
            codificação atualizadas com HTML5 limpo e CSS3.
          </p>
        </div>
        <div>
          <h2>Design e Art</h2>
          <p>
            Um site com design atrativo e responsivo gera mais satisfação e
            fidelização de clientes. Isso acontece porque o site se torna mais
            focado nas necessidades do público-alvo.
          </p>
        </div>
      </div>
    </div>
  </section>

  <section class="slogan-one">
    <div class="line"></div>
    <h2>
      Nosso trabalho geralmente incorpora tudo, desde o design da página de
      destino até o desenvolvimento de software personalizado e a criação
      complexa de e-commerce.
    </h2>
    <div class="line"></div>
    <button>ENTRE EM CONTATO</button>
  </section>

  <section class="culture-history">
    <div class="container-flex">
      <div class="redL">
        <h2>A GENTE SE ENVOLVE MAIS</h2>
        <p>
          Integramos informações com um processo de estruturação de dados para
          oferecer uma solução ideal além de utilizar modernas ferramentas e
          tecnologias disponíveis no mercado para oferecer soluções inovadoras
          aos nossos clientes.
        </p>
        <button>Saiba Mais</button>
      </div>
      <div class="imgR"></div>
    </div>

    <div class="container-flex">
      <div class="imgL"></div>
      <div class="redR">
        <h2>QUEREMOS CONTAR A SUA HISTÓRIA</h2>
        <p>
          Tudo começa com uma ideia. Talvez você queira abrir um negócio. Talvez
          você queira transformar um passatempo em algo mais sério. Ou talvez
          você tenha um projeto criativo para compartilhar com o mundo. O que
          quer que seja, a forma como você conta sua história on-line pode fazer
          toda a diferença.
        </p>
      </div>
    </div>
  </section>

  <section class="blog">
    <h1>Veja em Nosso Blog</h1>
    <div class="container-flex">
      <SmallCard
        image-url="blog1.png"
        card-title="A importância de estabelecer uma forte presença online"
        card-date="Publicado em 15 de janeiro de 2022"
        card-text="À medida que você começa a desenvolver uma marca, há uma infinidade de benefícios para se estabelecer no espaço online. Para começar, como vivemos em um mundo digital, você quer estar onde seus clientes estão – online! [...]"
      />
      <LargeCard
        image-url="blog3.png"
        card-title="É preciso um profissional para evitar erros no site que podem prejudicar uma pequena empresa"
        card-date="Publicado em 14 de janeiro de 2022"
        card-text="Quando os irmãos Jake e Mike Carroll lançaram a MagnaTech Autoglass em Federal Way, Washington, há três anos, eles fizeram muitas coisas certas. Eles tinham anos de experiência na indústria de vidros automotivos, elaboraram um plano de negócios direcionado a um nicho carente e escolheram um local onde o líder nacional do setor não tinha presença física. Mas quando se tratava de seu site, eles cometeram um erro comum. Em vez de recorrer a um designer de sites profissional, eles optaram por seguir o caminho do faça você mesmo (DIY). [...]"
      />
      <SmallCard
        image-url="blog2.png"
        card-title="Site estático ou dinâmico: qual é a melhor opção?"
        card-date="Publicado em 15 de Maio de 2022"
        card-text="Para criar uma página na web é necessário, antes de tudo, escolher entre um site estático ou um site dinâmico. As duas opções funcionam bem, no entanto, existem diferenças entre os modelos que devem ser levadas em consideração na hora de montar a sua página. [...]"
      />
    </div>
  </section>

  <section class="faq">
    <h1>Tem alguma Dúvida?</h1>
    <div class="accordion">
      <div class="line-white"></div>
      <h4 @click="faq1">O que é desenvolvimento de sites?</h4>
      <p id="faq1" hidden>
        O desenvolvimento web é a construção e manutenção de sites, é o trabalho
        que acontece nos bastidores para fazer um site parecer ótimo, trabalhar
        rápido e ter um bom desempenho com uma experiência perfeita do usuário.
        Desenvolvedores web, ou 'devs', fazem isso usando uma variedade de
        linguagens de codificação. Os idiomas que eles usam dependem dos tipos
        de tarefas que estão pré-definidas e das plataformas em que estão
        trabalhando. As habilidades de desenvolvedores web estão em alta demanda
        em todo o mundo. O campo de desenvolvimento da web é geralmente dividido
        em front-end (o lado voltado para o usuário) e back-end (o lado do
        servidor ou painel administrativo).
      </p>
      <div class="line-white"></div>
      <h4 @click="faq2">Quais tecnologias trabalhamos?</h4>
      <p id="faq2" hidden>
        Preferimos trabalhar com tecnologias de código aberto que tenham um
        futuro brilhante. As tecnologias específicas são Vue.js, PHP, MySQL,
        HTML5, CSS, JavaScript, etc. As tecnologias de código aberto são
        econômicas e apoiadas pela comunidade de desenvolvedores em todo o
        mundo. No entanto, podemos adaptar sua preferência tecnológica com base
        em suas necessidades. Caso sintamos que não podemos fazer o trabalho por
        qualquer motivo que seja, seremos francos sobre isso. Qualidade, ética e
        transparência impulsionam nossos negócios!
      </p>
      <div class="line-white"></div>
      <h4 @click="faq3">O site será otimizado para mecanismos de busca?</h4>
      <p id="faq3" hidden>
        O site será otimizado para mecanismos de buscas? Sim, nós fazemos e
        somos extremamente bons em SEO On-Page. Na verdade, todos os tipos de
        site que desenvolvemos incluem em sua estrutura otimização de sites
        (SEO), atualizada de acordo com as últimas atualizações dos sites de
        busca. Podemos executar SEO avançado também. Para SEO avançado, temos
        pacotes diferenciados onde vamos analisar suas palavras-chave, o código
        atual do seu site, etc. Fale conosco para explicarmos os detalhes!
      </p>
      <div class="line-white"></div>
      <h4 @click="faq4">Se eu quiser alterar o site futuramente?</h4>
      <p id="faq4" hidden>
        Depende das mudanças que você irá precisar. Realizamos pequenas
        alterações gratuitamente. No entanto, se o tempo necessário para os
        ajustes exceder 1 hora de trabalho, vamos preparar uma proposta que
        contenha o escopo, custos e termos e condições.<br /><br />E se eu
        quiser upgrades ou alterações em um site que foi desenvolvido por outra
        agência? Sim, nós trabalhamos em sites desenvolvidos por outros
        fornecedores. No entanto, esses sites levam mais tempo para
        refazer/modificar.
      </p>
      <div class="line-white"></div>
      <h4 @click="faq5">
        Meu site será responsível e amigável para dispositivos móveis?
      </h4>
      <p id="faq5" hidden>
        Sim. Seu site será totalmente responsivo e ficará ótimo em todos os
        dispositivos. Não cobramos extra por isso. Vem como padrão.
      </p>
      <div class="line-white"></div>
      <h4 @click="faq6">Preciso de hospedagem?</h4>
      <p id="faq6" hidden>
        Sim. Hospedagem do site é como alugar um espaço na internet. Você
        precisará dela, caso contrário as pessoas não poderão acessar seu site.
        A hospedagem geralmente custa menos de 50,00 por mês. Pode custar mais
        dependendo de suas necessidades. Os preços de hospedagem geralmente
        aumentam quanto mais visitantes do site você tem, quanto mais espaço
        necessita, quantidade de e-mails, entre outros fatores.<br /><br />Nós
        também oferecemos serviço de hospedagem personalizado, conforme as
        necessidades do seu site. Entre em contato conosco para mais informações
        sobre nossos planos de hospedagem.
      </p>
      <div class="line-white"></div>
      <h4 @click="faq7">Qual o preço do desenvolvimento de sites?</h4>
      <p id="faq7" hidden>
        O custo para desenvolver um site é a partir de 2.000,00. No entanto,
        depende de que tipo de site você precisa. O processo de criação e
        desenvolvimento exige muito tempo em planejamento e pesquisa. Ao
        contrário de outras agências, não usamos templates. Nós desenvolvemos
        seu site do zero, o que significa que você tem um design único sob
        medida em torno de seu negócio. Comprar um site nosso não deve
        simplesmente ser visto como uma despesa de negócios, e sim um
        investimento, pois seu site é uma ferramenta de vendas e irá obter
        retorno através dele.
      </p>
      <div class="line-white"></div>
      <h4 @click="faq8">Como vamos nos comunicar durante o desenvolvimento?</h4>
      <p id="faq8" hidden>
        Antes de começarmos a trabalhar juntos, teremos uma conversa para
        discutir o projeto. Assim que começarmos, a maior parte da comunicação
        ocorrerá por reuniões semanais ou quinzenais online, e toda decisão
        tomada será formalizada por e-mail. Isso torna o processo muito mais
        fácil, pois teremos todas as informações salvas e podemos voltar para
        ele mais tarde.<br /><br />Tudo o que construirmos será 100% propriedade
        sua. A maioria dos nossos clientes fica conosco por anos. Mas se por
        qualquer razão você decidir que deseja levar seu site para outro serviço
        de hospedagem ou outra empresa para atender o site, nós o ajudaremos com
        o mesmo esforço para fazer a transição da forma mais fácil e eficiente
        possível. O site é seu, afinal, e queremos que você o leve aonde quer
        que vá.
      </p>
      <div class="line-white"></div>
      <h4 @click="faq9">Posso atualizar meu site sozinho?</h4>
      <p id="faq9" hidden>
        Gostamos de oferecer a capacidade de nossos clientes atualizarem seus
        próprios sites, mas algumas tecnologias que utilizamos podem ser bem
        complicadas sem o conhecimento e formação adequados. Por isso, temos a
        opção de desenvolver seu site em uma plataforma fácil para gerenciar o
        conteúdo, de modo que você possa adicionar, editar e excluir conteúdo
        sem nos pagar para fazer isso por você.
      </p>
      <div class="line-white"></div>
    </div>
  </section>

  <section class="slogan-two">
    <h2>
      Somos conhecidos por desafiar a forma como as histórias digitais são
      contadas.
    </h2>
    <button>CONTE-NOS A SUA HISTÓRIA</button>
  </section>
  <Footer />
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import SmallCard from "@/components/SmallCard.vue";
import LargeCard from "@/components/LargeCard.vue";
import Footer from "@/components/Footer.vue"

export default {
  name: "HomeView",
  components: {
    Header,
    SmallCard,
    LargeCard,
    Footer,
  },
  methods: {
    faq1() {
      if (document.getElementById("faq1").hasAttribute("hidden"))
        document.getElementById("faq1").removeAttribute("hidden");
      else document.getElementById("faq1").setAttribute("hidden", "true");
    },
    faq2() {
      if (document.getElementById("faq2").hasAttribute("hidden"))
        document.getElementById("faq2").removeAttribute("hidden");
      else document.getElementById("faq2").setAttribute("hidden", "true");
    },
    faq3() {
      if (document.getElementById("faq3").hasAttribute("hidden"))
        document.getElementById("faq3").removeAttribute("hidden");
      else document.getElementById("faq3").setAttribute("hidden", "true");
    },
    faq4() {
      if (document.getElementById("faq4").hasAttribute("hidden"))
        document.getElementById("faq4").removeAttribute("hidden");
      else document.getElementById("faq4").setAttribute("hidden", "true");
    },
    faq5() {
      if (document.getElementById("faq5").hasAttribute("hidden"))
        document.getElementById("faq5").removeAttribute("hidden");
      else document.getElementById("faq5").setAttribute("hidden", "true");
    },
    faq6() {
      if (document.getElementById("faq6").hasAttribute("hidden"))
        document.getElementById("faq6").removeAttribute("hidden");
      else document.getElementById("faq6").setAttribute("hidden", "true");
    },
    faq7() {
      if (document.getElementById("faq7").hasAttribute("hidden"))
        document.getElementById("faq7").removeAttribute("hidden");
      else document.getElementById("faq7").setAttribute("hidden", "true");
    },
    faq8() {
      if (document.getElementById("faq8").hasAttribute("hidden"))
        document.getElementById("faq8").removeAttribute("hidden");
      else document.getElementById("faq8").setAttribute("hidden", "true");
    },
    faq9() {
      if (document.getElementById("faq9").hasAttribute("hidden"))
        document.getElementById("faq9").removeAttribute("hidden");
      else document.getElementById("faq9").setAttribute("hidden", "true");
    },
  },
};
</script>

<style scoped>
/* START OF SHOWCASE */
.showcase {
  height: 600px;
  background: url("@/assets/home-page/showcase/showcase.png") no-repeat;

  box-shadow: 0px 5px 50px 5px rgba(0, 0, 0, 0.5);
}
.showcase h1 {
  width: 820px;
  margin: 0 0 0 145px;
  padding-top: 145px;

  font-family: "Montserrat";
  font-style: normal;
  font-weight: 800;
  font-size: 64px;
  line-height: 78px;

  color: #ffffff;
}
.showcase h2 {
  margin: 12px 0 0 145px;

  font-family: "Georgia";
  font-style: normal;
  font-weight: 700;
  font-size: 24px;
  line-height: 150%;
  /* identical to box height, or 36px */

  letter-spacing: 0.04em;

  color: #ffffff;
}
.showcase h3 {
  margin: 30px 0 0 145px;

  font-family: "Montserrat";
  font-style: normal;
  font-weight: 800;
  font-size: 24px;
  line-height: 150%;
  /* identical to box height, or 36px */

  letter-spacing: 0.02em;
  text-transform: uppercase;

  color: #ffffff;
}
.showcase button {
  margin: 25px 0 0 145px;
  width: 400px;
  height: 50px;
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 800;
  font-size: 24px;
  line-height: 150%;
  /* identical to box height, or 36px */

  text-transform: uppercase;

  color: #ffffff;
  background: #9e2b20;
  border-radius: 8px;
  border-style: none;
  cursor: pointer;
}
/* END OF SHOWCASE */
/* START OF SERVICOS */
.servicos h1 {
  margin: 150px 0 0 80px;

  font-family: "Montserrat";
  font-style: normal;
  font-weight: 800;
  font-size: 64px;
  line-height: 150%;
  /* identical to box height, or 96px */

  letter-spacing: 0.025em;

  color: #000000;
}
.servicos .container-flex {
  display: flex;
  align-items: center;
  justify-content: space-around;
  flex-wrap: wrap;
}
.left {
  width: 595px;
}
.right {
  width: 595px;
  width: 620px;
}
.right div {
  height: 300px;
}
.servicos .left img {
  margin: 65px 0 0 0px;
}
.servicos .left p {
  margin: 20px 0 0 24px;

  font-family: "Lato";
  font-style: normal;
  font-weight: 500;
  font-size: 24px;
  line-height: 150%;
  /* identical to box height, or 36px */

  letter-spacing: 0.02em;

  color: #000000;
}
.servicos .right h2 {
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 800;
  font-size: 36px;
  /* identical to box height, or 54px */

  color: #000000;
}
.servicos .right p {
  font-family: "Lato";
  font-style: normal;
  font-weight: 400;
  font-size: 24px;

  /* or 36px */

  letter-spacing: 0.02em;

  color: #000000;
}
/* END OF SERVIÇOS */
/* START OF FIRST SLOGAN */
.slogan-one {
  text-align: center;
  margin: 150px 0 0 0;
}
.line {
  width: 80%;
  height: 0px;
  margin: auto;
  border: 1px solid #9e2b20;

  border-radius: 50px;
}

.slogan-one h2 {
  width: 95%;
  margin: 75px auto 75px auto;

  font-family: "Georgia";
  font-style: normal;
  font-weight: 700;
  font-size: 28px;
  line-height: 150%;
  /* or 42px */

  text-align: center;
  letter-spacing: 0.02em;

  color: #000000;
}
.slogan-one button {
  margin-top: 110px;
  width: 634px;
  height: 50px;

  border-style: none;

  background: #9e2b20;
  border-radius: 8px;

  font-family: "Montserrat";
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 150%;
  /* identical to box height, or 36px */

  text-align: center;

  color: #ffffff;

  cursor: pointer;
}
.culture-history .container-flex {
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
}
.culture-history {
  margin: 150px 0 0 0;
}
.culture-history .redL,
.culture-history .redR {
  width: 50%;
  height: 600px;

  background: #9e2b20;
}
.culture-history h2 {
  margin: 115px 0 0 60px;
  width: 85%;

  font-family: "Montserrat";
  font-style: normal;
  font-weight: 800;
  font-size: 36px;
  /* identical to box height, or 54px */

  text-transform: uppercase;

  color: #ffffff;
}
.culture-history .redL p,
.culture-history .redR p {
  margin: 50px 0 0 60px;
  width: 85%;
  height: 165px;

  font-family: "Lato";
  font-style: normal;
  font-weight: 400;
  font-size: 22px;
  line-height: 150%;
  /* or 33px */

  letter-spacing: 0.02em;

  color: #ffffff;
}
.culture-history .imgR {
  background: url("@/assets/home-page/cultura-historia/office-peope.png")
    no-repeat;
  width: 50%;
  height: 600px;
}
.culture-history .imgL {
  background: url("@/assets/home-page/cultura-historia/gathering.png") no-repeat;
  width: 50%;
  height: 600px;
}
.culture-history .redL button {
  margin: 50px 0 0 60px;
  width: 262px;
  height: 50px;

  background: #3f130e;
  border-radius: 12px;
  border-style: none;

  font-family: "Montserrat";
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 150%;
  /* identical to box height, or 36px */

  color: #ffffff;

  cursor: pointer;
}
/* END OF CULTURE-HISTORY */
/* START OF BLOG */
.blog {
  background: url("@/assets/home-page/blog/background-pattern.png") no-repeat;
  background-size: cover;
  height: 1118px;
}
.blog h1 {
  padding: 150px 0 0 0;
  margin: 0 0 0 80px;

  font-family: "Montserrat";
  font-style: normal;
  font-weight: 800;
  font-size: 64px;
  line-height: 150%;
  /* identical to box height, or 96px */

  letter-spacing: 0.025em;

  color: #000000;
}
.blog .container-flex {
  margin: 65px 0 0 0;
  display: flex;
  align-items: center;
  justify-content: space-around;
  flex-wrap: wrap;
}
/* END OF BLOG */
/* START OF FAQ */
.faq {
  background: #9e2b20;
  padding: 150px 0 150px 0;
}
.faq h1 {
  margin: 0 0 60px 80px;

  font-family: "Montserrat";
  font-style: normal;
  font-weight: 800;
  font-size: 64px;
  line-height: 150%;
  /* identical to box height, or 96px */

  letter-spacing: 0.025em;

  color: #ffffff;
}
.faq h4 {
  width: 75%;
  margin: auto;

  font-family: "Georgia";
  font-style: normal;
  font-weight: 700;
  font-size: 28px;
  line-height: 150%;
  /* identical to box height, or 42px */

  letter-spacing: 0.025em;

  color: #ffffff;

  cursor: pointer;
}
.faq .line-white {
  margin: 15px auto 15px auto;

  width: 80%;
  height: 0px;
  border: 1px solid white;

  border-radius: 50px;
}
.faq p {
  padding: 15px 0 15px 0;
  width: 70%;
  margin: auto;

  font-family: "Lato";
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 150%;
  /* or 36px */

  letter-spacing: 0.02em;

  color: white;
}
/* END OF FAQ */
/* START OF SLOGAN 2 */
.slogan-two {
  text-align: center;
  padding: 85px 0 85px 0;
}
.slogan-two h2 {
  width: 95%;
  margin: auto;

  font-family: "Georgia";
  font-style: normal;
  font-weight: 700;
  font-size: 28px;
  line-height: 150%;
  /* or 42px */

  letter-spacing: 0.02em;

  color: #000000;
}
.slogan-two button {
  margin: 45px auto 0 auto;
  width: 500px;
  height: 50px;

  background: #9e2b20;
  border-radius: 12px;
  border-style: none;

  cursor: pointer;

  font-family: "Montserrat";
  font-style: normal;
  font-weight: 800;
  font-size: 24px;
  line-height: 150%;
  /* identical to box height, or 36px */

  letter-spacing: 0.02em;

  color: #ffffff;
}
</style>
