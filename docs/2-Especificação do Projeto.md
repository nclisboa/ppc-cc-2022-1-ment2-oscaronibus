# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

Camila Silva tem 09 anos, é uma criança com deficiência visual permanente. Ela é uma garota que sempre quis praticar esportes e poder interagir com outras crianças em diversas atividades em um ambiente seguro e acessível.

Pedro Alves tem 23 anos, por conta de um infeliz acidente acabou parcialmente deficiente visual. Ele quer se adaptar e voltar a se integrar a sociedade, mas não tem meios e nem conhecimento. Além encontrar um ambiente que possa lhe fornecer melhores condições de acessibilidade.

Luis Gomes tem 45 anos, é programador Front-End. Sempre busca ajudar o próximo com ações beneficientes e está em busca de instituições para apoiar, tanto como voluntário ou com doações.

## Histórias de Usuários

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE`              | PARA ... `MOTIVO/VALOR`                             |
|--------------------|-------------------------------------------------|-----------------------------------------------------|
| Pedro Alves        | Ter controle sobre minhas ações no site/Mobile  | Entender passo a passo das minhas ações             |
| Pedro Alves        | Seja audiovisual                                | Facilitar a navegação dentro do site/mobile         |
| Pedro Alves        | Saber sobre a intituição                        | Verificar se essa instituição encaixa em meu ideais |
| Pedro Alves        | Encontrar informações de contato/localidade     | Facilitar a comunicação com a intituição            |
| Camila Silva       | Encontrar atividades oferecidas                 | Participar das atividades da instituição            |
| Luis Gomes         | Contribuir para com a instituição               | Ser como um voluntário ou com doações               |


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.


### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| mostrar a todo momento informações de contato. | ALTA | 
|RF-002| O uso de cor deve apresentar um alto contraste.   | ALTA |
|RF-003|No contraste proporção mínima recomendada de 4,5:1 para textos grandes e 7:1 para outros textos e imagens.  | MÉDIA |
|RF-004| Ter links informativos, por exemplo no link aparecer “meu perfil” em vez de “clique aqui”, ou o URL completo.   | MÉDIA |
|RF-005| Ter texto grande e alinhado à esquerda.| ALTA | 
|RF-006| Usar texto além da formatação, pois é possível que os leitores de tela não identifiquem negrito ou destaques.   | BAIXA |
|RF-007| Permitir que o usuário utilize o zoom em até 200% sem prejudicar o conteúdo. | Média | 
|RF-008| Atalhos para conteúdo via teclado, como “tab” para trocar de páginas.  | Média |
|RF-009| Botões com frase em imagens. | Média | 
|RF-010| Utilizar conteúdo em áudiovisual.   | Média |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 


## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |
