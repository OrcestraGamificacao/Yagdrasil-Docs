# Documento de Visão

## Histórico de Versionamento
Data | Versão | Descrição | Autor |
---- | ------ | --------- | ----- |
23/11/2020 | 0.1 | Tópicos 4.1, 4.2 | Natan Santana |
15/03/2021 | 0.2 | Tópicos 3.1, 3.2, 3.3, 3.7 | Lucas Macedo |
17/03/2021 | 0.3 | Tópico 6 | Luiz Henrique |
18/03/2021 | 0.4 | Tópicos 1.1, 1.2, 1.3 e 1.4 | Fellipe Araujo |

## 1. Introdução

### 1.1 Propósito
<p style="text-align: justify;">&emsp;&emsp;
Este documento apresenta o detalhamento e as justificativas referentes ao desenvolvimento do projeto Yagdrasil, além de deixar explícito o contexto em que este software atuará. Este documento visa, também, apresentar modelos para representar o funcionamento e os detalhes do software.
</p>

### 1.2 Escopo
<p style="text-align: justify;">&emsp;&emsp;
O Documento de Visão tem o objetivo de deixar explícito os problemas em que o projeto Yagdrasil se propõe a resolver e as soluções em que o mesmo se propõe a adotar para atingir seu objetivo. É importante ressaltar que este documento será evoluído ao decorrer do desenvolvimento do projeto.
</p>

### 1.3 Definições, Acrônimos e Abreviações
Termo | Descrição |
----- | --------- |
KipoKM | Startup do grupo gestão inovadora |
Gamificação | É o uso de mecânicas e características de jogos para engajar, motivar comportamentos e facilitar o aprendizado de pessoas em situações reais, normalmente não relacionados a jogos |
Framework | Na gamificação, é uma abstração de um conjunto de técnicas de design de gamificação que podem ser aplicadas, independente do contexto, para desenvolver um produto gamificado |
Frontend | Parte visual de uma aplicação (interface gráfica) com o qual um usuário possa interagir |
Backend | Parte de um software responsável pelas regras de negócios da aplicação |

### 1.4 Visão Geral
<p style="text-align: justify;">&emsp;&emsp;
A ideia principal deste Documento de Visão é fornecer de maneira objetiva e organizada as características e utilidades da aplicação, além dos assuntos que tangem à problemática inicial, o posicionamento do produto, o detalhamento dos perfis interessados e dos usuários, recursos, restrições e requisitos do produto.
</p>

## 2. Posicionamento
### 2.1 Oportunidade de Negócios

### 2.2 Instrução do Problema

### 2.3 Instrução de Posição do Produto

## 3. Descrições da Parte Interessada e do Usuário

### 3.1 Dados Demográficos do Mercado

<p style="text-align: justify;">&emsp;&emsp;
A Orc’estra Gamificação tem como um dos seus principais serviços a criação de um software gamificado, de forma para dar maior engajamento aos usuários ao utilizar o produto. A Empresa Júnior já trabalhou em vários projetos de desenvolvimento, recebendo nota promissora ao executá-la, entregando um produto de qualidade ao final. O jardim do conhecimento foi pensado e elaborado da melhor forma para que o usuário guie-se pelo caminho consiga entender os projetos internos da Empresa. Os benefícios deste projeto atende toda a KipoKm, dando uma maior autonomia aos usuários para se atualizar sobre os projetos em andamento. 
</p>

### 3.2 Resumo da parte interessada

Nome | Representa | Função
---- | ---------- | ------
Administradores | Figura de criador dos projetos  | O administrador será responsável por criar os cards de projetos que está ocorrendo na empresa
Usuário Interno | Funcionários que utilizam o software | Responsáveis por entender sobre o conteúdo, compreendendo o escopo dos projetos 

### 3.3 Resumo do Usuário

<p style="text-align: justify;">&emsp;&emsp;
 O usuário terá acesso ao mapa, onde ele vai pesquisar um conteúdo de sua preferência e assim localizar o jardim. Ao entrar, o usuário seleciona uma árvore referente ao tema de estudo, e assim, clicando na folha, conseguirá ter acesso aos dados do projeto, adquirindo conhecimento sobre a data que foi pedida, aos detalhes do projeto e os responsáveis por este. O sistema de cores será responsável por saber qual objeto ele já visualizou e o que foi visualizado, vendo seu progresso realizado. 
 </p> 	

### 3.7 Principais Necessidades da Parte Interessada ou do Usuário

1. Tabela da parte interessada

Necessidade | Prioridade | Solução Atual | Solução Proposta
----------- | ---------- | ------------- | ----------------
O usuário necessita ter acesso a tela do jardim | Alta | O usuário ao buscar o conteúdo que queira na tela principal, será apresentado no mapa mundi plano os jardins de sua preferência. | Criar um mapa do mundo em 3d para que o usuário possa localizar o jardim escolhido ao pesquisar sobre o assunto preferido.

## 4. Visão Geral do Produto

### 4.1 Perspectiva do Produto

<p style="text-align: justify;"> &emsp;&emsp;
O Jardim do Conhecimento é um software web gamificado que permite a gestão conhecimento de forma visual, ágil e dinâmica, promovendo a interação e engajamento de pessoas. Dessa forma, o acesso ao conhecimento se dá através de uma sequência de menus, mapas, jardins, árvores, dentre outros elementos que promovem uma interação dinâmica e atualização em tempo real. A plataforma oferecerá uma ferramenta de busca para facilitar a seleção dos jardins de conhecimento, além de mostrar a trilha de conhecimento do usuário de acordo com seu progresso, fornecendo constante feedback.
</p>

### 4.2 Resumo das Capacidades

Benefício para o Cliente | Recursos de Suporte
------------------------ | -------------------
Facilidade para selecionar jardins de conhecimento: | Será apresentado ao usuário um mapa com uma barra de pesquisa que ao ser usada pesquisando por nome de projetos, região, área do conhecimento e pessoas, será apresentado no mapa vários pontos que representam jardins.
Acompanhar a trilha de Conhecimento Pessoal: |Ao entrar em um Jardim, aparecerá algumas áreas que representam diferentes áreas de conhecimento, contendo vários tipos de subáreas e projetos. A medida que o usuário leia os conteúdos da árvore, a mesma muda de cor de vermelho (não realizou nada em determinada parte da trilha de conhecimento) para amarelo (a realização das atividades está em andamento) e depois para verde (finalizou determinada parte da trilha de conhecimento). O usuário, além de poder ler os conteúdos, poderá realizar processos/projetos. Além disso, esse progresso será mostrado no Jardim Pessoal do usuário, disponibilizando as árvores que já foram acessadas.
 

## 5. Recursos do Produto

### 5.1 Recurso 1

### 5.2 Recurso 2

## 6. Restrições

* A Orc’estra Gamificação deverá desenvolver o Frontend da aplicação e realizar a integração com o Backend desenvolvido pela KipoKM;
* O Frontend da aplicação será desenvolvido utilizando a biblioteca React do JavaScript;
* O Backend deverá ser desenvolvido em uma linguagem que possibilita a integração com o ReactJS;
* O Backend deverá possuir as regras de negócio para o funcionamento do Software;
* O Backend deverá possuir os dados de negócios necessários para o funcionamento do Frontend;
* O Backend deverá ser disponibilizado em tempo hábil a Orc’estra Gamificação para integração com o Frontend.
