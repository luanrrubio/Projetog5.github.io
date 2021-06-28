# Especificações do Projeto
<p>A participação dos usuários foi o pontapé inicial para que pudessemos determinar o déficit no mercado que este projeto iria suprir. O processo foi feito a partir das observações feitas pelas personas em entrevistas, compreendendo, desta forma, as necessidades dos usuários alvo do projeto.</p>
<p>Os dados foram coletados a partir de Personas e Histórias de usuários.</p>

## Personas
<p>Segue abaixo as Personas consultadas durante o processo de especificação:</p>
<div>
 <table>
  <thead>
        <th></th>
        <th>Rafaela Santos</th>
        <th>Felipe Ramos</th>

  </thead>

  <tbody id="tbody">
        <td><b>Idade</b></td>
        <td>37 anos</td>
        <td>30 anos</td>

   <tr><td><b>Ocupação </b></td>
    <td>Desenvolvedor FrontEnd</td>
    <td>Diretor de Design Gráfico focado em Marketing</td></tr>
    <tr><td><b>Experiência</b></td>
    <td>
     <ul>
      <li>Trabalhou como Dev Junior em uma StartUp focada em desenvolvimento Web;</li>
      <li>Javascript (React)</li>
      <li>HTML5</li>
      <li>CSS (BootStrap)</li>
      <li>Integração com APIs REST</li>
     </ul>
    </td>
    <td>
     <ul>
      <li>Direção Criativa;</li>
      <li>Domínio do pacote Adobe Creative Suite: Photoshop, Illustrator e InDesign;</li>
      <li>Conhecimento em Pacote Office;</li>
      <li>Replicar elementos de uma identidade visual com consistência;</li>
      <li>Domínio em After Effects.</li>
     </ul></td></tr>
     <tr><td><b>Redes de contato/procura de projetos</b></td>
     <td>
     <ul>
      <li>Linkedin</li>
      <li>Github</li>
      <li>Instagram</li>
     </ul></td>
     <td>
     <ul>
      <li>Linkedin</li>
      <li>Github</li>
      <li>Instagram</li>
      <li>Twitter</li>
     </ul></td></tr>
     <tr><td><b>Frustrações</b></td>
     <td>
     <ul>
      <li>Depois de pedir demissão da StartUp com o intuito de trabalhar como Freelancer, não consegui encontrar um site que organizasse os anúncios de oportunidade de projeto.</li><br>
      <li>Não estou conseguindo trabalho de forma consistente, por não ter uma base de clientes para oferecer meus serviços.</li>
     </ul></td>
      <td><ul><li>Apesar do interesse em fazer projetos fora da empresa em que trabalha, acha muito trabalhoso encontrar anúncios recentes de projeto;</li>
       <li>Não encontrou uma rede eficiente em que consiga anunciar seu trabalho como Freelancer;</li>
       <li>Não conseguir encontrar pessoas para realizar projetos específicos fora da empresa com facilidade</li>
     </ul> </td></tr>
  </tbody>
 </table>
</div>

## Histórias de Usuários

<p>Foram registradas as seguintes histórias de usuário, a partir das necessidades das personas identificadas para o projeto:</p>

   <table class="table">
    <thead>
     <th>Eu como [Persona]</th>
      <th>Quero/Desejo</th>
       <th>Para</th>
    </thead>
    
   <tbody id="tbody">
     <td>Rafaela Santos</td>
     <td>Conseguir localizar anúncios com oportunidades de projetos Freelancer facilmente.</td>
     <td>Conseguir trabalhar de forma remota, sem uma relação empregatícia tradicional.</td>

   <tr><td>Rafaela Santos</td>
       <td>Interagir com empresas que possuem demandas de projetos Freelancer</td>
       <td>Estar inserida no mercado de trabalho, mesmo trabalhando de casa, principalmente durante a pandemia</td></tr>
   <tr><td>Rafaela Santos</td>
       <td>Estar atualizada em relação às novas necessidades de mercado na área de programação</td>
       <td>Construir uma relação de clientes para que eu possa manter este estilo de vida, trabalhando de forma remota e autônoma</td></tr>
   <tr><td>Felipe Ramos</td>
       <td>Encontrar vagas disponíveis para projetos pontuais</td>
       <td>Incrementar minha renda</td></tr>
       <tr><td>Felipe Ramos</td>
       <td>Poder realizar uma pesquisa sobre prestadores de serviço disponíveis na área do Design Gráfico</td>
       <td>Contactar e contratar, se estiver precisando, para realizar projetos pontuais para mim e/ou para a empresa em que trabalho </td></tr>
   </tbody>
  </table>


## Requisitos do Projeto
<p>As possibilidades de interação dos usuários com o produto final é definido a partir dos requisitos funcionais e não funcionais. É necessário a descrição da prioridade destes requisitos, assim, determinando os aspectos que o sistema deverá apresentar quando estiver concluído.</p>

### Requisitos Funcionais

<p>A tabela a seguir apresentará os requisitos funcionais do projeto, discriminando o nível de prioridade estabelecido entre cada elemento.</p>

<table class="table">
  <thead>
   <th>ID</th>
   <th>Descrição</th>
   <th>Prioridade</th>
  </thead>

  <tbody id="tbody">
   <td><b>RF-01</b></td>
   <td>O site deve deixar claro para o usuário qual o seu objetivo principal</td>
   <td>Alta</td>

   <tr>
    <td><b>RF-02</b></td>
    <td>O site deve possuir um menu que leve o usuário até os anúncios de prestadores de serviço ou para que o usuário se cadastre e ofereça seus serviços</td>
    <td>Alta</td>
   </tr>
   <tr>
    <td><b>RF-03</b></td>
    <td>O site deve possuir um filtro para cada especialização na página de amostragem dos Desenvolvedores disponíveis</td>
    <td>Alta</td>
   </tr>
   <tr>
    <td><b>RF-04</b></td>
    <td>O site deve permitir o compartilhamento de informações entre prestadores de serviço e contratantes, possibilitando o processo de Networking.</td>
    <td>Alta</td></tr>
    <tr><td><b>RF-05</b></td>
    <td>O site deve padronizar as informações necessárias para que um anúncio seja feito, tanto para procura de projetos, quanto para demanda de prestadores de serviço</td>
    <td>Alta</td>
   </tr>
   <tr>
    <td><b>RF-06</b></td>
    <td>O site deve ter uma ferramenta de remoção de anúncios de vagas que já foram ocupadas e/ou de anúncios de prestadores de serviço que não estão mais disponíveis</td>
    <td>Alta</td>
   </tr>
   <tr>
    <td><b>RF-07</b></td>
    <td>O site deve permitir a visualização de quantas pessoas se aplicaram para determinado anúncio ou contactaram determinado prestador de serviço</td>
    <td>Média</td>
   </tr>
   <tr>
    <td><b>RF-08</b></td>
    <td>O site deve oferecer ferramentas para criação de um perfil personalizado, em que a Empresa/Pessoa Física ou prestador de serviço possa específicar seus requisítos, habilidades.</td>
    <td>Média</td>
   </tr>
  </tbody>
 </table>


### Requisitos não Funcionais

<p>A tabela a seguir apresentará os requisitos não funcionais do projeto, discriminando o nível de prioridade estabelecido entre cada elemento.</p>

<table class="table">
 <thead>
  <th>ID</th>
  <th>Descrição</th>
  <th>Prioridade</th>
 </thead>

 <tbody id="tbody">
  <td><b>RNF-01</b></td>
  <td>O projeto deve ser publicado em um ambiente acessível</td>
  <td>Alta</td>

  <tr>
   <td><b>RNF-02</b></td>
   <td>O projeto deverá estar adequado para qualquer tipo de dispositivo que acesse possa acessa-lo, mobile, desktop, notebook...</td>
   <td>Alta</td>
  </tr>
  <tr>
   <td><b>RNF-03</b></td>
   <td>O site deve ser estéticamente agradável, contrastando-se entre os demais elementos ofertados pelos desenvolvedores.</td>
   <td>Média</td>
  </tr>
  <tr>
   <td><b>RNF-04</b></td>
   <td>O site deve apresentar compatibilidade com os navegadores web do mercado, focando nos mais utilizados(Microsoft Edge, Mozilla Firefox, Google Chrome).</td>
   <td>Alta</td></tr>
  </tr>
 </tbody>
</table>

## Restrições


<p>As restrições para o desenvolvimento deste projeto, configurando-se nas limitações pré-definidas para a sua execução estão dispostas na tabela a seguir.</p>
<table class="table">
  <thead>
   <th>ID</th>
   <th>Descrição</th>
  </thead>

  <tbody id="tbody">
   <td><b>RE-01</b></td>
   <td>O projeto deverá ser desenvolvido até o final do semestre letivo.</td>
   <tr>
    <td><b>RE-02</b></td>
    <td>As tecnologias utilizadas no projeto se restringirão às tecnologias básicas de Web FrontEnd</td>
   </tr>
   <tr>
    <td><b>RE-03</b></td>
    <td>Os desenvolvedores do projeto não poderão contratar terceiros para a realização do desenvolvimento do trabalho.</td>
   </tr>
  </tbody>
 </table>


