# Informações do Projeto
`TÍTULO DO PROJETO`  

E-WASTE

`CURSO` 

Análise e Desenvolvimento de Sistemas/Sistemas de Informação

## Participantes

Os membros do grupo são: 

> - Rafael Felipe de Paula Silva
> - Pedro Augustto dos Santos Barbosa
> - Davi Lucas do Carmo Nogueira
> - Bernardo Azevedo Estrela
> - Heloisa Almeida de Paula
> - Pedro Henrique Ferreira Gomes Martins

# Estrutura do Documento

- [Informações do Projeto](#informações-do-projeto)
  - [Participantes](#participantes)
- [Estrutura do Documento](#estrutura-do-documento)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Público-Alvo](#público-alvo)
- [Especificações do Projeto](#especificações-do-projeto)
  - [Personas e Mapas de Empatia](#personas-e-mapas-de-empatia)
  - [Histórias de Usuários](#histórias-de-usuários)
  - [Requisitos](#requisitos)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos não Funcionais](#requisitos-não-funcionais)
  - [Restrições](#restrições)
- [Projeto de Interface](#projeto-de-interface)
  - [User Flow](#user-flow)
  - [Wireframes](#wireframes)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)
  - [Controle de Versão](#controle-de-versão)
- [**############## SPRINT 1 ACABA AQUI #############**](#-sprint-1-acaba-aqui-)
- [Projeto da Solução](#projeto-da-solução)
  - [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [Arquitetura da solução](#arquitetura-da-solução)
- [Avaliação da Aplicação](#avaliação-da-aplicação)
  - [Plano de Testes](#plano-de-testes)
  - [Ferramentas de Testes (Opcional)](#ferramentas-de-testes-opcional)
  - [Registros de Testes](#registros-de-testes)
- [Referências](#referências)


# Introdução

## Problema

Um grande problema que atinge a sociedade moderna é o excesso de lixo eletrônico, pois na era digital possuir algum equipamento eletrônico desatualizado se tornou algo extremamente comum. Entretanto o descarte dos mesmos é um desafio e tanto, pois o descarte incorreto pode afetar diretamente o meio ambiente, com isso deve ser feito o descarte em locais específicos, porém onde exatamente deve ser descartado? A grande maioria da população desconhece pontos de descarte adequados e com isso acumulam lixo eletrônico de forma desnecessária, com isso em mente trouxemos a ferramenta E-WASTE.

> Nesse momento você deve apresentar o problema que a sua aplicação deve
> resolver. No entanto, não é a hora de comentar sobre a aplicação.
> Descreva também o contexto em que essa aplicação será usada, se
> houver: empresa, tecnologias, etc. Novamente, descreva apenas o que de
> fato existir, pois ainda não é a hora de apresentar requisitos
> detalhados ou projetos.
>
> Nesse momento, o grupo pode optar por fazer uso
> de ferramentas como Design Thinking, que permite um olhar de ponta a
> ponta para o problema.
>
> **Links Úteis**:
> - [Objetivos, Problema de pesquisa e Justificativa](https://medium.com/@versioparole/objetivos-problema-de-pesquisa-e-justificativa-c98c8233b9c3)
> - [Matriz Certezas, Suposições e Dúvidas](https://medium.com/educa%C3%A7%C3%A3o-fora-da-caixa/matriz-certezas-suposi%C3%A7%C3%B5es-e-d%C3%BAvidas-fa2263633655)
> - [Brainstorming](https://www.euax.com.br/2018/09/brainstorming/)

## Objetivos

O objetivo principal desse software é desenvolver uma interface web que seja para indicar virtualmente os locais corretos de descarte de lixo eletrônico em Betim. Dentro do software será possível pesquisar os locais de descarte por bairro, além disso será possivél verificar quais lixos eletrônicos são aceitos para serem descartados. 

> Aqui você deve descrever os objetivos do trabalho indicando que o
> objetivo geral é desenvolver um software para solucionar o problema
> apresentado acima. Apresente também alguns (pelo menos 2) objetivos
> específicos dependendo de onde você vai querer concentrar a sua
> prática investigativa, ou como você vai aprofundar no seu trabalho.
> 
> **Links Úteis**:
> - [Objetivo geral e objetivo específico: como fazer e quais verbos utilizar](https://blog.mettzer.com/diferenca-entre-objetivo-geral-e-objetivo-especifico/)

## Justificativa

O descarte incorreto de lixo eletrônico pode causar um grande impacto na sociedade, pois polui o ambiente e muita das vezes alguém pode vir a se machucar por manusear de forma incorreta esses lixos descartados. Existem diversos pontos de descarte espalhados pela cidade de Betim, porém a grande maioria da população desconhece esses locais. E por esse fato nosso software é uma ótima solução para este problema, pois irá mostrar de forma bem objetiva a importância do descarte correto e aonde descartar os mesmos.  

> Descreva a importância ou a motivação para trabalhar com esta aplicação
> que você escolheu. Indique as razões pelas quais você escolheu seus
> objetivos específicos ou as razões para aprofundar em certos aspectos
> do software.
> 
> O grupo de trabalho pode fazer uso de questionários, entrevistas e
> dados estatísticos, que podem ser apresentados, com o objetivo de
> esclarecer detalhes do problema que será abordado pelo grupo.
>
> **Links Úteis**:
> - [Como montar a justificativa](https://guiadamonografia.com.br/como-montar-justificativa-do-tcc/)

## Público-Alvo

Nosso público-alvo será qualquer cidadão Betinense que possuir algum lixo eletrônico, seja idoso, seja jovem, seja adulto, não importa a idade ou profissão, todos produzem lixo eletrônico e por esse fato ter uma ferramenta que mostre onde descartar seria bem útil e vantajoso. 

> Descreva quem serão as pessoas que usarão a sua aplicação indicando os
> diferentes perfis. O objetivo aqui não é definir quem serão os
> clientes ou quais serão os papéis dos usuários na aplicação. A ideia
> é, dentro do possível, conhecer um pouco mais sobre o perfil dos
> usuários: conhecimentos prévios, relação com a tecnologia, relações
> hierárquicas, etc.
>
> Adicione informações sobre o público-alvo por meio de uma descrição
> textual, ou diagramas de personas, mapa de stakeholders, ou como o
> grupo achar mais conveniente.
> 
> **Links Úteis**:
> - [Público-alvo: o que é, tipos, como definir seu público e exemplos](https://klickpages.com.br/blog/publico-alvo-o-que-e/)
> - [Qual a diferença entre público-alvo e persona?](https://rockcontent.com/blog/diferenca-publico-alvo-e-persona/)
 
# Especificações do Projeto

O E-WASTE tem como obejtivo mostrar de forma intuitiva locais de descarte de lixo eletrônico em Betim, nosso público-alvo serão todos os cidadãos Betinenses que possuirem lixo eletrônico que precisa ser descartado. Nosso site terá uma interface simples, pois tem como objetivo ser intuitiva e direta com nosso objetivo, terá também uma paleta de cores com verde e branco para mostrar que realmente nos impostamos com o descarte correto para evitar danos a natureza. O site poderá ser visitado tanto em dispositivos movéis ou desktops. Entre as funções do site, podemos destacar as seguintes:
1.Cadastro de novos usuários;
2.Cadastro do Administrador;
3.Controle de todos os usuários cadastrados;
4.Possibilidade de encontrar locais de descarte através da pesquisa por bairro ou rua;
5.Possibilidade do usuário sugerir locais de descarte não cadastrados;
6.O administrador poderá adicionar novos locais de descarte e modificar os já existentes;
7.Terá uma área que mostrará um pouco da importância do descarte correto do lixo eletrônico.
Temos a intenção de adicionar mais e mais funções ao sistema no futuro, mas no momento nossa preocupação é em garantir que o site funcione de maneira correta e que ajude os cidadãos Betinenses no descarte correto de seus lixos eletrônicos.


> Apresente uma visão geral do que será abordado nesta parte do
> documento, enumerando as técnicas e/ou ferramentas utilizadas para
> realizar a especificações do projeto

## Personas e Mapas de Empatia

Sendo mais especifico, temos nossas possíveis personas as quais direcionaremos a exposição da ideia que a partir deles se espalhe para o resto do público-alvo. Entre nossas personas temos a viciada em jogos online, o que gosta de ler muito, o que ama a natureza e a que ama assistir séries e filmes. 


> Relacione as personas identificadas no seu projeto e os respectivos mapas de empatia. Lembre-se que 
> você deve ser enumerar e descrever precisamente e de forma
> personalizada todos os principais envolvidos com a solução almeja. 
> 
> Para tanto, baseie-se tanto nos documentos disponibilizados na disciplina
> e/ou nos seguintes links:
>
> **Links Úteis**:
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Como fazer um mapa de empatia - Vídeo](https://www.youtube.com/watch?v=JlKHGpVoA2Y)
> 
> 
> **Exemplo de Persona 01**
> 
> ![Exemplo de Persona](imaages/../images/persona01-LAYLA.jpg)
> ![Exemplo de Persona](imaages/../images/empatialayla.png)
>
> 
> **Exemplo de Persona 02**
> 
> ![Exemplo de Persona](imaages/../images/Persona-MIA.png)
> 
> **Exemplo de Persona 03**
> 
> ![Exemplo de Persona](imaages/../images/Persona-Solange.png)
> 
> **Exemplo de Persona 04**
> 
> ![Exemplo de Persona](imaages/../images/Persona-Julieta.png)
> 
> **Exemplo de Persona 05**
> 
> ![Exemplo de Persona](imaages/../images/Persona-Cecilia.jpg)
> ![Exemplo de Persona](imaages/../images/empati-cec.png)
> 
> Fonte: [Como criar uma persona para o seu negócio](https://raissaviegas.com.br/como-criar-uma-persona/)


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE`          |PARA ... `MOTIVO/VALOR`                                    |
|--------------------|---------------------------------------------|-----------------------------------------------------------|
|Usuário do sistema  | Localizar pontos de descarte próximos       | Descartar meu lixo eletrônico acumulado                   |
|Usuário do sistema  | Cadastrar meu usuário                       | Para acessar o software                                   |
|Usuário do sistema  | Saber a importância do descarte correto     | Para ter conhecimento sobre o que está sendo feito        |
|Administrador       | Alterar permissões                          | Permitir que possam administrar contas                    |
|Administrador       | Ter acesso ao cadastro de pontos de descarte| Para adicionar pontos novos ou modificar os já existentes |

> Apresente aqui as histórias de usuário que são relevantes para o
> projeto de sua solução. As Histórias de Usuário consistem em uma
> ferramenta poderosa para a compreensão e elicitação dos requisitos
> funcionais e não funcionais da sua aplicação. Se possível, agrupe as
> histórias de usuário por contexto, para facilitar consultas
> recorrentes à essa parte do documento.
>
> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário se cadastre para ter acesso | ALTA | 
|RF-002| Permitir ao administrador se cadastrar ao software | ALTA |
|RF-003| Permitir que o usuário busque por bairros os pontos de descarte existentes   | ALTA |
|RF-004| Permitir que o usuário faça sugestões de locais de descarte não cadastrados| MÉDIA |
|RF-005| Permitir que o administrador cadastre novos pontos de descarte| ALTA |
|RF-006| Terá uma área que mostrará a importância do descarte correto | BAIXA |
|RF-007| Ao clicar em um dos locais de descarte cadastrado o usuário será redirecionado ao Google Maps| MÉDIA |



### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel e Desktop (Chrome, Safari, Oracle) | ALTA | 
|RNF-002| Deve processar requisições do usuário em no máximo 5s |  MÉDIA |
|RNF-003| O sistema deve garantir a segurança dos dados do administrador e dos usuários | MÉDIA |
|RNF-004| O site terá uma paleta de cores com verde e branco | ALTA |

> Com base nas Histórias de Usuário, enumere os requisitos da sua
> solução. Classifique esses requisitos em dois grupos:
>
> - [Requisitos Funcionais (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
>   correspondem a uma funcionalidade que deve estar presente na
>   plataforma (ex: cadastro de usuário).
>
> - [Requisitos Não Funcionais (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
>   correspondem a uma característica técnica, seja de usabilidade,
>   desempenho, confiabilidade, segurança ou outro (ex: suporte a
>   dispositivos iOS e Android).
>
> Lembre-se que cada requisito deve corresponder à uma e somente uma
> característica alvo da sua solução. Além disso, certifique-se de que
> todos os aspectos capturados nas Histórias de Usuário foram cobertos.
> 
> **Links Úteis**:
> 
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)


## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


> Enumere as restrições à sua solução. Lembre-se de que as restrições
> geralmente limitam a solução candidata.
> 
> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)


# Projeto de Interface

Entrando no site o usuário deverá realizar o login, caso não tenha o cadastro deverá realizar o cadastro. Após o cadastro, o usuário será redirecionado a página inicial do E-WASTE, onde poderá ir em um guia que irá mostrar os pontos de descarte próximos, porém o usuário poderá pesquisar outros pontos de coleta em diferentes bairros. Além disso terá uma área que terá um texto que falará sobre a importância do descarte correto de lixos eletrônicos. Terá também uma aba onde será possível solicitar o cadastro de novos locais de descarte que não aparecem so site. 

> Apresente as principais interfaces da solução. Discuta como 
> foram elaboradas de forma a atender os requisitos funcionais, não
> funcionais e histórias de usuário abordados nas [Especificações do
> Projeto](#especificações-do-projeto).

## User Flow

![Exemplo de UserFlow](images/Userflow.jpg)

> Fluxo de usuário (User Flow) é uma técnica que permite ao desenvolvedor
> mapear todo fluxo de telas do site ou app. Essa técnica funciona
> para alinhar os caminhos e as possíveis ações que o usuário pode
> fazer junto com os membros de sua equipe.
>
> **Links Úteis**:
> - [User Flow: O Quê É e Como Fazer?](https://medium.com/7bits/fluxo-de-usu%C3%A1rio-user-flow-o-que-%C3%A9-como-fazer-79d965872534)
> - [User Flow vs Site Maps](http://designr.com.br/sitemap-e-user-flow-quais-as-diferencas-e-quando-usar-cada-um/)
> - [Top 25 User Flow Tools & Templates for Smooth](https://www.mockplus.com/blog/post/user-flow-tools)
>
> **Exemplo**:
>
> 


## Wireframes

 ![Exemplo de Wireframe](images/wireframe.png)

> Wireframes são protótipos das telas da aplicação usados em design de interface para sugerir a
> estrutura de um site web e seu relacionamentos entre suas
> páginas. Um wireframe web é uma ilustração semelhante ao
> layout de elementos fundamentais na interface.
> 
> **Links Úteis**:
> - [Ferramentas de Wireframes](https://rockcontent.com/blog/wireframes/)
> - [Figma](https://www.figma.com/)
> - [Adobe XD](https://www.adobe.com/br/products/xd.html#scroll)
> - [MarvelApp](https://marvelapp.com/developers/documentation/tutorials/)
> 
> **Exemplo**:
> 
>


# Metodologia

......  COLOQUE AQUI O SEU TEXTO ......

> Nesta parte do documento, você deve apresentar a metodologia 
> adotada pelo grupo, descrevendo o processo de trabalho baseado nas metodologias ágeis, 
> a divisão de papéis e tarefas, as ferramentas empregadas e como foi realizada a
> gestão de configuração do projeto via GitHub.
>
> Coloque detalhes sobre o processo de Design Thinking e a implementação do Framework Scrum seguido
> pelo grupo. O grupo poderá fazer uso de ferramentas on-line para acompanhar
> o andamento do projeto, a execução das tarefas e o status de desenvolvimento
> da solução.
> 
> **Links Úteis**:
> - [Tutorial Trello](https://trello.com/b/8AygzjUA/tutorial-trello)
> - [Gestão ágil de projetos com o Trello](https://www.youtube.com/watch?v=1o9BOMAKBRE)
> - [Gerência de projetos - Trello com Scrum](https://www.youtube.com/watch?v=DHLA8X_ujwo)
> - [Tutorial Slack](https://slack.com/intl/en-br/)

## Divisão de Papéis

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente a divisão de papéis e tarefas entre os membros do grupo.
>
> **Links Úteis**:
> - [11 Passos Essenciais para Implantar Scrum no seu Projeto](https://mindmaster.com.br/scrum-11-passos/)
> - [Scrum em 9 minutos](https://www.youtube.com/watch?v=XfvQWnRgxG0)


## Ferramentas

......  COLOQUE AQUI O SEU TEXTO - SIGA O EXEMPLO DA TABELA ABAIXO  ......

| Ambiente  | Plataforma              |Link de Acesso |
|-----------|-------------------------|---------------|
|Processo de Design Thinkgin  | Miro |  https://miro.com/XXXXXXX | 
|Repositório de código | GitHub | https://github.com/XXXXXXX | 
|Hospedagem do site | Heroku |  https://XXXXXXX.herokuapp.com | 
|Protótipo Interativo | MavelApp ou Figma | https://figma.com/XXXXXXX | 

>
> Liste as ferramentas empregadas no desenvolvimento do
> projeto, justificando a escolha delas, sempre que possível.
> 
> As ferramentas empregadas no projeto são:
> 
> - Editor de código.
> - Ferramentas de comunicação
> - Ferramentas de diagramação
> - Plataforma de hospedagem
> 
> O editor de código foi escolhido porque ele possui uma integração com o
> sistema de versão. As ferramentas de comunicação utilizadas possuem
> integração semelhante e por isso foram selecionadas. Por fim, para criar
> diagramas utilizamos essa ferramenta por melhor captar as
> necessidades da nossa solução.
> 
> **Links Úteis - Hospedagem**:
> - [Getting Started with Heroku](https://devcenter.heroku.com/start)
> - [Crie seu Site com o HostGator](https://www.hostgator.com.br/como-publicar-seu-site)
> - [GoDady](https://br.godaddy.com/how-to)
> - [GitHub Pages](https://pages.github.com/)

## Controle de Versão

......  COLOQUE AQUI O SEU TEXTO ......

> Discuta como a configuração do projeto foi feita na ferramenta de
> versionamento escolhida. Exponha como a gerência de tags, merges,
> commits e branchs é realizada. Discuta como a gerência de issues foi
> realizada.
> A ferramenta de controle de versão adotada no projeto foi o
> [Git](https://git-scm.com/), sendo que o [Github](https://github.com)
> foi utilizado para hospedagem do repositório `upstream`.
> 
> O projeto segue a seguinte convenção para o nome de branchs:
> 
> - `master`: versão estável já testada do software
> - `unstable`: versão já testada do software, porém instável
> - `testing`: versão em testes do software
> - `dev`: versão de desenvolvimento do software
> 
> Quanto à gerência de issues, o projeto adota a seguinte convenção para
> etiquetas:
> 
> - `bugfix`: uma funcionalidade encontra-se com problemas
> - `enhancement`: uma funcionalidade precisa ser melhorada
> - `feature`: uma nova funcionalidade precisa ser introduzida
>
> **Links Úteis**:
> - [Tutorial GitHub](https://guides.github.com/activities/hello-world/)
> - [Git e Github](https://www.youtube.com/playlist?list=PLHz_AreHm4dm7ZULPAmadvNhH6vk9oNZA)
> - [5 Git Workflows & Branching Strategy to deliver better code](https://zepel.io/blog/5-git-workflows-to-improve-development/)
>
> **Exemplo - GitHub Feature Branch Workflow**:
>
> ![Exemplo de Wireframe](images/Github-Workflow.png)

# **############## SPRINT 1 ACABA AQUI #############**


# Projeto da Solução

......  COLOQUE AQUI O SEU TEXTO ......

## Tecnologias Utilizadas

......  COLOQUE AQUI O SEU TEXTO ......

> Descreva aqui qual(is) tecnologias você vai usar para resolver o seu
> problema, ou seja, implementar a sua solução. Liste todas as
> tecnologias envolvidas, linguagens a serem utilizadas, serviços web,
> frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.
> Apresente também uma figura explicando como as tecnologias estão
> relacionadas ou como uma interação do usuário com o sistema vai ser
> conduzida, por onde ela passa até retornar uma resposta ao usuário.
> 
> Inclua os diagramas de User Flow, esboços criados pelo grupo
> (stoyboards), além dos protótipos de telas (wireframes). Descreva cada
> item textualmente comentando e complementando o que está apresentado
> nas imagens.

## Arquitetura da solução

......  COLOQUE AQUI O SEU TEXTO E O DIAGRAMA DE ARQUITETURA .......

> Inclua um diagrama da solução e descreva os módulos e as tecnologias
> que fazem parte da solução. Discorra sobre o diagrama.
> 
> **Exemplo do diagrama de Arquitetura**:
> 
> ![Exemplo de Arquitetura](images/arquitetura-exemplo.png)


# Avaliação da Aplicação

1. *Facilidade de Uso*: Verificar se a aplicação é intuitiva para os usuários encontrarem pontos de descarte e registrarem o lixo eletrônico.

2. *Abrangência*: Avaliar se a aplicação cobre uma ampla área geográfica, mostrando pontos de descarte em diferentes regiões.

3. *Precisão e Atualização*: Verificar se as informações sobre os pontos de descarte estão corretas e atualizadas, evitando que usuários se desloquem para pontos que não existem mais.

4. *Acessibilidade*: Analisar se a aplicação é acessível para diferentes dispositivos (computador, celular) e se possui recursos para usuários com necessidades especiais.

5. *Feedback e Suporte*: Verificar se a aplicação fornece feedback claro aos usuários sobre seus registros e se há suporte caso surjam problemas ou dúvidas.

6. *Segurança*: Avaliar a segurança dos dados inseridos pelos usuários, garantindo a proteção das informações pessoais.

7. *Requisitos Legais*: Certificar-se de que a aplicação cumpre com as leis e regulamentações locais relacionadas ao descarte de lixo eletrônico.

## Plano de Testes


1. *Registro de Novo Ponto de Descarte*: Testar o processo de registro de um novo ponto de descarte para garantir que as informações sejam inseridas corretamente e sejam exibidas no mapa.

2. *Busca por Tipo de Lixo Eletrônico*: Verificar se a busca por tipo de lixo eletrônico (baterias, celulares, eletrônicos maiores, etc.) retorna resultados relevantes e precisos.

3. *Atualização de Informações*: Testar a capacidade de atualização das informações de um ponto de descarte existente, incluindo horário de funcionamento, tipos de lixo aceitos, etc.

4. *Navegabilidade no Mapa*: Verificar se o mapa utilizado para exibir os pontos de descarte é fácil de navegar, se permite zoom, se é responsivo e se fornece informações claras ao usuário.

5. *Testes de Performance*: Avaliar a performance do site, especialmente quando há aumento do tráfego de usuários buscando pontos de descarte em determinados momentos do dia ou em eventos específicos.

6. *Teste de Responsividade*: Verificar se o site é responsivo em diferentes dispositivos (computadores, tablets, smartphones) e se a experiência do usuário é consistente.

7. *Testes de Segurança*: Avaliar a segurança do site, garantindo que os dados dos usuários estejam protegidos e que não haja vulnerabilidades de acesso não autorizado.

8. *Testes de Integração com GPS*: Se houver integração com GPS, verificar se a localização é precisa e se direciona corretamente os usuários até o ponto de descarte selecionado.

9. *Testes de Compatibilidade do Navegador*: Verificar se o site funciona corretamente nos principais navegadores (Chrome, Firefox, Safari, etc.) e se a experiência do usuário não é comprometida.

10. *Testes de Usabilidade*: Avaliar a experiência do usuário em todo o processo, desde a busca até o registro do descarte, identificando possíveis pontos de confusão ou dificuldade.

## Ferramentas de Testes (Opcional)

Vscode e Replit. O Visual Studio Code (VSCode) é uma IDE (Ambiente de Desenvolvimento Integrado) muito popular entre desenvolvedores devido à sua versatilidade, extensibilidade e facilidade de uso. Ele oferece uma ampla gama de extensões que ajudam a melhorar a produtividade e facilitam o processo de desenvolvimento em várias linguagens de programação.

Para testes de programação, você pode encontrar extensões no VSCode que oferecem suporte para testes unitários, frameworks de testes, debuggers e até mesmo integrações com ferramentas de automação de testes. Isso ajuda a realizar testes de código de forma mais eficiente e completa.

Se tiver mais informações sobre a ferramenta que deseja saber ou se o nome foi digitado incorretamente, ficarei feliz em fornecer informações mais específicas sobre sua usabilidade em testes de programação.

## Registros de Testes


1. *Interface Intuitiva*: A navegação é simples e fácil para encontrar os pontos de descarte de lixo eletrônico. A disposição dos elementos na interface torna a busca eficiente e amigável.

2. *Informações Abrangentes*: Os detalhes sobre cada ponto de descarte são completos, incluindo tipos de lixo aceitos, horários de funcionamento, endereço e informações de contato.

3. *Mapa Interativo*: A integração do mapa é eficaz, permitindo aos usuários visualizar os pontos de descarte de forma clara e identificar facilmente a localização mais conveniente.

*Possíveis Falhas e Melhorias:*

1. *Atualização de Informações*: Algumas informações sobre os pontos de descarte podem estar desatualizadas, o que pode levar a usuários se deslocando para locais que não aceitam mais determinados tipos de lixo eletrônico. Melhoria: Implementar um sistema de verificação regular e incentivar os usuários a relatar mudanças nos pontos de descarte.

2. *Performance*: Durante períodos de tráfego intenso, o site pode apresentar lentidão ou instabilidade. Melhoria: Realizar testes de carga para identificar e resolver possíveis gargalos na capacidade do servidor.

3. *Falta de Cobertura*: Em algumas áreas geográficas, a cobertura de pontos de descarte pode ser limitada. Melhoria: Incentivar parcerias com mais locais de descarte ou incentivar a criação de novos pontos.

4. *Feedback aos Usuários*: A falta de feedback claro após o registro de um novo ponto de descarte pode deixar os usuários sem confirmação sobre a efetiva inclusão da informação. Melhoria: Implementar um sistema de confirmação após o registro, indicando que o ponto foi inserido com sucesso.

5. *Acessibilidade*: Pode haver limitações de acessibilidade para usuários com deficiências visuais ou motoras. Melhoria: Realizar testes de acessibilidade e implementar ajustes para garantir que o site seja inclusivo para todos os usuários.

# Referências


1. *O que é lixo eletrônico e como descartá-lo corretamente:*
   [https://www.recicloteca.org.br/o-que-e-lixo-eletronico/](https://www.recicloteca.org.br/o-que-e-lixo-eletronico/)

2. *Legislação sobre descarte de resíduos eletrônicos no Brasil:*
   [https://www.mma.gov.br/responsabilidade-socioambiental/residuos-solidos/lixo-eletronico](https://www.mma.gov.br/responsabilidade-socioambiental/residuos-solidos/lixo-eletronico)

3. *Guia prático para descarte responsável de lixo eletrônico:*
   [https://www.greenme.com.br/viver/sustentabilidade/3336-lixo-eletronico-como-descartar](https://www.greenme.com.br/viver/sustentabilidade/3336-lixo-eletronico-como-descartar)

4. *Iniciativas e programas de reciclagem de eletrônicos no Brasil:*
   [https://www.sindireceita.org.br/inicial/reciclagem-de-lixo-eletronico/](https://www.sindireceita.org.br/inicial/reciclagem-de-lixo-eletronico/)

5. *Impacto ambiental do descarte incorreto de lixo eletrônico:*
   [https://www.nationalgeographicbrasil.com/meio-ambiente/2020/08/impacto-ambiental-do-lixo-eletronico-e-o-que-fazer-para-evitar](https://www.nationalgeographicbrasil.com/meio-ambiente/2020/08/impacto-ambiental-do-lixo-eletronico-e-o-que-fazer-para-evitar)
