## Tech Challenge 5 🚀

Este projeto foi desenvolvido por:

<ul>
  <li><a href="https://github.com/CleudemirFaccoJr" target="blank">Cleudemir Facco Junior - RM: 362556</a></li>
  <li><a href="https://github.com/Nsingrid" target="blank">Ingrid Nascimento - RM: 362259</a></li>
  <li><a href="https://github.com/jhonsoad" target="_blank">Jhonatas Magalhães - RM: 364576</a></li>
  <li><a href="https://github.com/joaodos3v" target="_blank">João Vitor - RM: 361587</a></li>
  <li><a href="https://github.com/kauelivio" target="_blank">Kauê Livio - RM: 362404</a></li>
</ul>

<p>Visto que possuimos duas visualizações para o MindEase (Mobile e Web) criamos ramificações desta documentação afim de que o que é específico de mobile, fique restrito ao diretório mobile e o de web fique apenas no web.</p>

#### 🌐 Documentação Web 
[> Aplicação Web do sistema](https://github.com/TC5Hackatton/web)

#### 📱 Documentação Mobile
[> Aplicação Mobile do sistema](https://github.com/TC5Hackatton/mobile)

# Sobre o MindEase
Em um mundo digital cada vez mais acelerado e visualmente poluído, a concentração e o bem-estar mental tornaram-se artigos de luxo. Para indivíduos neurodivergentes ou pessoas que enfrentam desafios como burnout, TDAH e ansiedade, essa realidade é ainda mais intensa. O MindEase nasceu não como mais um aplicativo de tarefas, mas como uma resposta direta a essa dor: uma ferramenta de produtividade projetada desde sua concepção para ser um santuário digital, onde a organização e o foco andam de mãos dadas com o conforto e a acessibilidade.

Nosso projeto se sustenta em três pilares fundamentais que demonstram uma maturidade técnica e uma visão de produto que transcendem o ambiente acadêmico:

### Acessibilidade
Nós não construímos um aplicativo para depois "adicionar" recursos de acessibilidade. Nós projetamos uma experiência fundamentalmente acessível e a transformamos em um aplicativo.

<ul>
  <li><b>Modo Escuro</b>: Nosso modo escuro vai além da estética. É uma ferramenta de design inclusivo, pensada para reduzir a sobrecarga sensorial em usuários com autismo e a fadiga visual em casos de enxaqueca. Utilizamos um contraste cuidadosamente otimizado — evitando o preto absoluto — para prevenir o "efeito halo" que pode dificultar a leitura para pessoas com dislexia, garantindo conforto e legibilidade.</li>
  <li><b>Empoderamento do Usuário</b>: A personalização é total. O usuário pode ajustar o tamanho da fonte e definir tempos padrão para suas tarefas, assumindo o controle de sua experiência e adaptando o ambiente digital às suas necessidades sensoriais e de foco.</li>
</ul>

### Arquitetura Profissional - Clean Architecture
Sob uma interface intuitiva e acolhedora, reside uma arquitetura de software robusta, escalável e de padrão industrial: a Clean Architecture.

<ul>
  <li><b>Estrutura Profissional</b>: A separação clara entre as camadas de Domínio (regras de negócio), Infraestrutura (tecnologias) e Apresentação (UI) é um diferencial técnico imenso. Isso demonstra não apenas a capacidade de codificar, mas de projetar sistemas complexos que são fáceis de manter, testar e evoluir — uma prática comum em equipes de alta performance no mercado.</li>
  <li><b>Tecnologia de Ponta</b>: Adotamos um stack moderno e poderoso com React Native, Expo, TypeScript e Firebase, garantindo uma aplicação multiplataforma, segura e com uma base de código limpa e previsível.</li>
</ul>

### Testes Automatizados
Para nosso público-alvo, um comportamento inesperado no software não é um mero inconveniente; é uma quebra de confiança que pode gerar ansiedade e frustração. Por isso, a qualidade não foi negociável.

<ul>
  <li><b>Cobertura Abrangente</b>: Atingimos a impressionante marca de 282 testes automatizados aprovados, distribuídos em 38 suítes de teste. Essa cobertura não é superficial: ela valida desde as regras de negócio mais críticas na camada de Domínio até a reatividade e consistência dos componentes de interface, como cronômetros e a troca de temas.</li>
  <li><b>Garantia de Confiabilidade</b>: Essa cultura de testes rigorosa, utilizando Jest e React Testing Library, assegura que o MindEase seja uma ferramenta estável e previsível. É a nossa promessa de que o aplicativo será um espaço seguro e livre de estresse, onde o usuário pode confiar plenamente na tecnologia para organizar sua vida.</li>
</ul>

O MindEase é a materialização de um processo de desenvolvimento que une propósito social com as melhores e mais modernas práticas de engenharia de software. Este projeto não entrega apenas as funcionalidades esperadas de um gestor de tarefas; ele entrega uma aplicação coesa, resiliente, profundamente humana e pronta para o mercado.

# 1 - Identidade Visual
<p><b>MindEase</b> - Organize com calma, produza com foco.<br/>
O MindEase surge com o objetivo é facilitar a vida acadêmica e profissional de pessoas neurodivergentes e/ou com desafios de processamento cognitivo.
O site e o aplicativo foram pensados para que o usuário não tenha mais um cansaço mental ao navegar nos sistemas.
Portanto a escolha das cores e fontes tenta refletir esta mensagem.</p>

## 1.1 - Paleta de Cores
<p>A escolha da paleta de cores visa equilibrar energia e o relaxamento. Cores mais neutras foram empregadas em tons suavez para que o usuário não tenha cansaço, ou force muito a vista durante o uso continuo da ferramenta:
 <ul>
  <li><img src="https://img.shields.io/static/v1?label=&message=%20&color=E59886&style=for-the-badge" height="20"> | '#E59886' | Coral Suave: Representa a vitalidade, o calor humano e a criatividade. É uma cor que chama a atenção sem causar o alerta agressivo do vermelho.</li>
  <li><img src="https://img.shields.io/static/v1?label=&message=%20&color=5B8DBE&style=for-the-badge" height="20"> | '#5B8DBE' | Azul Serenidade: A cor da confiança e da estabilidade. No app, ela guia o usuário pelo fluxo de trabalho de forma pacífica, reduzindo a ansiedade de ter muitas tarefas.</li>
  <li><img src="https://img.shields.io/static/v1?label=&message=%20&color=A8DBA8&style=for-the-badge" height="20"> | '#A8DBA8' | Verde Equilíbrio: Transmite crescimento, renovação e a sensação de "dever cumprido" ao concluir uma tarefa.</li>
  <li><img src="https://img.shields.io/static/v1?label=&message=%20&color=F5D06C&style=for-the-badge" height="20"> | '#F5D06C' | Amarelo Suave: Utilizado para estados "em andamento", trazendo otimismo e foco na ação presente.</li>
  <li><img src="https://img.shields.io/static/v1?label=&message=%20&color=2C3E50&style=for-the-badge" height="20"> | '#2C3E50' | Marinho Profundo (Texto/Contraste): Substitui o preto puro para dar uma leitura mais suave e moderna, mantendo a autoridade.</li>
 </ul>
</p>
## 1.2 - Tipografia
<p>O logotipo utiliza fontes com contrastes que comunicam a essência do produto:
<ul>
  <li>Mind | "Caviar Dreams" | O uso de uma fonte sem serifa, estruturada e em negrito, comunica organização, clareza e seriedade. É o lado "lógico" do planejamento.</li>
  <li>Ease | "Freestyle Script" | A fonte cursiva e fluida representa a flexibilidade, a leveza e o toque humano. Ela quebra a rigidez da lista de tarefas, lembrando que a vida deve fluir.</li>
  <li>Corpo do Texto | "Raleway" | Para a interface, utilizamos fontes de alta legibilidade, com traços arredondados que mantêm a amigabilidade do design.</li>
</ul>
</p>

## 2. Iconografia e Elementos Visuais
<p>
  <ul>
    <li>O Símbolo (Cérebro): Desenhado com linhas orgânicas e suaves, o ícone do cérebro não é clínico, mas sim convidativo. Ele reforça que o app cuida do seu principal ativo: sua mente.</li>
    <li>Cards Arredondados: O uso de border-radius generoso (cantos bem arredondados) remove a agressividade visual das quinas, tornando a interface mais "gentil" aos olhos.</li>
    <li>Espaçamento (White Space): O layout prioriza o respiro. Menos informação visual por tela significa menos carga cognitiva para o usuário.</li>
  </ul>
</p>

## 3. Modo Escuro (Dark Mode)
<p>A paleta de modo escuro foi projetada para uso noturno ou para usuários com sensibilidade visual. O fundo em <img src="https://img.shields.io/static/v1?label=&message=%20&color=2C3E50&style=for-the-badge" height="20">Marinho Profundo reduz a emissão de luz azul, enquanto os tons de azul e verde pastéis mantêm o contraste necessário para o foco sem agredir a visão.</p>

## 4. Logotipo
O logotipo do aplicativo consiste em uma simbolo: cérebro. E o nome do app em duas fontes distintas na intenção de trazer leveza e simplicidade para o entendimento do foco do aplicativo/sistema.

<table border="0">
  <tr>
    <td align="center" width="250">
      <img width="230" height="245" alt="MindEase Logo Vertical - Modo Claro" src="https://github.com/user-attachments/assets/68838cc1-2d04-48fa-93cc-9777cfc226c6" /><br />
      <sub>Logo MindEase vertical modo claro.</sub>
    </td>
    <td align="center" width="250">
      <img width="231" height="245" alt="MindEase Logo Vertical - Modo Escuro" src="https://github.com/user-attachments/assets/7f16b52c-c77d-4e4a-975e-ba7dc3742797" /<br />
      <sub>Logo MindEase vertical modo escuro.</sub>
    </td>
  </tr>

   <tr>
    <td align="center" width="250">
      <img width="411" height="142" alt="MindEase Logo Horizontal - Modo Claro" src="https://github.com/user-attachments/assets/6ba323df-ef1c-465f-b389-aef55a983300" /><br />
      <sub>Logo MindEase horizontal modo claro.</sub>
    </td>
    <td align="center" width="250">
      <img width="411" height="144" alt="MindEase Logo Horizontal - Modo Escurot" src="https://github.com/user-attachments/assets/ebcad11c-8c04-45d1-8b57-a61dc7958abd" /><br />
      <sub>Logo MindEase horizontal modo escuro.</sub>
    </td>
  </tr>
</table>

#### 4.1 - O Conceito
A identidade visual do MindEase nasce da intersecção entre a necessidade de estrutura e o desejo de leveza. Entendemos que mentes neurodivergentes não precisam de "conserto", mas de um ambiente que respeite seu funcionamento único. O logotipo reflete isso: uma base sólida para o pensamento (Mind) que flui naturalmente para a simplificação (Ease).

#### 4.2 - Pilares da Comunicação Visual
<ul>
  <li>Clareza Sem Ruído: Assim como nosso logo, a interface do app prioriza o respiro visual. Menos ícones, mais significado.</li>
  <li>Cromoterapia Cognitiva: Utilizamos tons que reduzem a fadiga ocular, ideal para períodos longos de estudo ou trabalho.</li>
  <li>Tipografia Inclusiva: A combinação de fontes auxilia na hierarquia da informação, ajudando o usuário a identificar rapidamente o que é prioridade (foco no TDAH e Dislexia).</li>
</ul>

#### 5 - Capturas de Tela
Como o Hackaton refere-se a dois sistemas, distintos porém integrados, as capturas de tela estão separadas por aplicação. Desta forma temos os prints:

##### 5.1 Mobile
<table border="0">
  <thead>
    <tr>
      <th colspan="5" align="center"><h5>Mobile - Modo Claro</h5></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center" width="250"><img width="1080" height="2424" alt="SplashScreen" src="https://github.com/user-attachments/assets/afba6aa0-54df-4b74-ac02-0cf6cde44421" />
      <sub>SplashScreen MindEase.</sub>
      </td>
      <td align="center" width="250"><img width="1080" height="2424" alt="Dashboard" src="https://github.com/user-attachments/assets/034dd27a-8b21-458a-8488-16f7729b26cf" />
      <sub>Dashboard MindEase.</sub>
      </td>
      <td align="center" width="250"><img width="1080" height="2424" alt="Listagem de Tarefas_1" src="https://github.com/user-attachments/assets/7dea9d70-76f5-4171-8e01-1a07b89562dc" />
      <sub>Listagem de Tarefas - TODO</sub>
      </td>
      <td align="center" width="250"><img width="1080" height="2424" alt="Listagem de Tarefas_2" src="https://github.com/user-attachments/assets/39f7035d-0df8-471c-952f-fd2ddb617454" />
      <sub>Listagem de Tarefas - DOING</sub>
      </td>
      <td align="center" width="250"><img width="1080" height="2424" alt="Listagem de Tarefas_3" src="https://github.com/user-attachments/assets/1224a85f-55b6-4794-8c96-6f8e585afb86" />
      <sub>Listagem de Tarefas - DONE</sub>
      </td>
    </tr>
    <tr>
      <td align="center" width="250"><img width="1080" height="2424" alt="Cadastro de Tarefa" src="https://github.com/user-attachments/assets/728eefa6-5026-48ac-80da-a997503f7f34" />
      <sub>Cadastro de Tarefa</sub>
      </td>
      <td align="center" width="250">
        <img width="1875" height="925" alt="ModoFoco" src="https://github.com/user-attachments/assets/1b3d0a32-bf22-4097-a6fa-56be42077a09" />
        <sub>Modo Foco no Mobile</sub>
      </td>
      <td align="center" width="250">
        <img width="1080" height="2424" alt="Screenshot_1772722672" src="https://github.com/user-attachments/assets/23613dcd-898c-4cf7-9500-29042d9f7170" />
        <sub>Preferências - Ajuste do Tamanho da fonte para melhor leitura (P)</sub>
      </td>
      <td align="center" width="250">
        <img width="1080" height="2424" alt="Screenshot_1772722669" src="https://github.com/user-attachments/assets/339d36fc-96eb-4ca4-ad31-2b990f0e5be2" />
        <sub>Preferências - Ajuste do Tamanho da fonte para melhor leitura (M - Default)</sub>
      </td>
      <td align="center" width="250">
        <img width="1080" height="2424" alt="Screenshot_1772722674" src="https://github.com/user-attachments/assets/6471fc98-4e61-4ded-8a27-dd994d73e0ad" />
        <sub>Preferências - Ajuste do Tamanho da fonte para melhor leitura (G)</sub>
      </td>
    </tr>
  </tbody>
</table>

<table border="0">
  <thead>
    <tr>
      <th colspan="5" align="center"><h5>Mobile - Modo Escuro</h5></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center" width="250"><img width="1080" height="2424" alt="Screenshot_1772379970" src="https://github.com/user-attachments/assets/db54a602-9bc9-4b87-b134-90a9d099f1b4" />
      <sub>Dashboard MindEase.</sub>
      </td>
      <td align="center" width="250"><img width="1080" height="2424" alt="Screenshot_1772379978" src="https://github.com/user-attachments/assets/2ba5b122-c747-44e2-9512-dfe3abe69486" />
      <sub>Preferências do Sistema</sub>
      </td>
      <td align="center" width="250"><img width="1080" height="2424" alt="Screenshot_1772379980" src="https://github.com/user-attachments/assets/e37a51c5-5952-4218-9057-fc37c670300e" />
      <sub>Preferências do Sistema - 2</sub>
      </td>
    </tr>
    <tr>
      <td align="center" width="250"><img width="1080" height="2424" alt="Screenshot_1772380092" src="https://github.com/user-attachments/assets/a74142e9-5230-480f-b886-1d8fc1e83c93" />
      <sub>Cadastro de Tarefa</sub>
      </td>
    </tr>
  </tbody>
</table>

O sistema oferece suporte nativo aos modos claro e escuro na maioria das interfaces. Esta funcionalidade vai além da estética: é uma ferramenta de acessibilidade cognitiva. Para usuários com TDAH ou sensibilidade sensorial, a alternância de temas ajuda a reduzir a fadiga visual e o 'ruído' na tela, facilitando a manutenção do foco e a organização mental durante o uso prolongado.

##### 5.2 Web

<table border="0">
  <thead>
    <tr>
      <th colspan="3" align="center"><h5>Web - Modo Claro</h5></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center" width="600">
        <img width="1875" height="925" alt="image" src="https://github.com/user-attachments/assets/28bf41ad-8ba6-4cfb-890b-338c0ecb817d" />
        <sub>Tela de Login - Web</sub>
      </td>
      <td align="center" width="600">
        <img width="1875" height="925" alt="image" src="https://github.com/user-attachments/assets/24e188ef-4297-41f0-b52c-bb28dd1969a1" />
        <sub>Tela de Cadastro</sub>
      </td>
      <td align="center" width="600">
      <img width="1875" height="925" alt="image" src="https://github.com/user-attachments/assets/c8535313-33e7-4923-830d-53ca95de7c54" />
      <sub>Tela de Dashboard</sub>
      </td>
    </tr>
    <tr>
      <td align="center" width="600">
        <img width="1875" height="925" alt="image" src="https://github.com/user-attachments/assets/2ef6ee0e-ee8f-4197-96fd-c5bf4e029c8a" />
        <sub>Tela de Visualização de Tarefas</sub>
      </td>
      <td align="center" width="600">
        <img width="1875" height="925" alt="image" src="https://github.com/user-attachments/assets/ea38df61-37d3-4fcf-875c-e2b7cfa3f8de" />
        <sub>Modal para cadastro de uma nova tarefa - Cronômetro</sub>
      </td>
       <td align="center" width="600">
        <img width="1875" height="925" alt="image" src="https://github.com/user-attachments/assets/eb3f2eed-2e60-4456-bac4-cf809032cceb" />
        <sub>Modal para cadastro de uma nova tarefa - Tempo Fixo</sub>
      </td>
    </tr>
    <tr>
      <td align="center" width="600">
      <img width="1873" height="922" alt="image" src="https://github.com/user-attachments/assets/985a49ae-f538-4ecb-a5f8-77da695575d4" />
      <sub>Preferências - Ajuste do Tamanho da fonte para melhor leitura (P)</sub>
      </td>
       <td align="center" width="600">
         <img width="1875" height="925" alt="image" src="https://github.com/user-attachments/assets/884758ef-4fc7-492e-a097-b1e641cb1609" />
         <sub>Preferências - Ajuste do Tamanho da fonte para melhor leitura (M - Default)</sub>
      </td>
      <td align="center" width="600">
         <img width="1872" height="923" alt="image" src="https://github.com/user-attachments/assets/1a40f3b7-b4c4-4676-9814-df17567032b7" />
         <sub>Preferências - Ajuste do Tamanho da fonte para melhor leitura (G)</sub>
      </td>   
    </tr>
    <tr>
      <td align="center" width="600">
         <img width="2875" height="1464" alt="image" src="https://github.com/user-attachments/assets/9b31ed77-f8ac-453a-9e41-e54946e90dcb" />
         <sub>Modo Foco Web</sub>
      </td> 
      <td align="center" width="600">
         <img width="1600" height="815" alt="image" src="https://github.com/user-attachments/assets/e61d3b40-5dbc-4f26-962d-fc60435e4cdb" />
         <sub>Modo Foco Web</sub>
      </td>  
    </tr>  
  </tbody>
</table>
