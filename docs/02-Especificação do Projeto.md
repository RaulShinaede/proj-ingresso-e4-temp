# Especificações do Projeto

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

## Personas
Seguem demonstradas por meio dos quadros apresentados o levantamento feito das personas e suas características durante o processo de entendimento do problema:

<table>
  <tr>
   <td width="1000" colspan="5" align="center">[NOME], [IDADE] anos.</td>
  </tr>
  <tr>
   <td width="200" align="center" height="200" rowspan="3"><img alt="[IMAGEM]" src=""></td>
   <td width="150" align="center">Ocupação</td>
   <td colspan="3">[OCUPAÇÃO]</td>
   <tr>
    <td width="150" align="center">Aplicativos</td>
    <td width="210" align="center">Motivações</td>
    <td width="210" align="center">Frustrações</td>
    <td width="240" align="center">Hobbies, História</td>
   </tr>
  </tr>
  <tr>
   <td>
    ●	APP 1<br>
    ●	APP 2<br>
   </td>
   <td>
    ●	MOTIVAÇÃO 1.<br>
    ●	MOTIVAÇÃO 2.<br>
   </td>
   <td>
    ●	FRUSTRAÇÃO 1<br>
    ●	FRUSTRAÇÃO 2<br>
   </td>
   <td>
    ●	HOBBIE 1<br>
    ●	HOBBIE 2<br>
   </td>
  </tr>
 </table>


## Histórias de Usuários

A fim de buscar mais informações sobre os motivos e causas de uso dessas pessoas a plataforma a ser desenvolvida, foram realizadas perguntas por meio de entrevistas, tendo resultados demonstrados no quadro apresentado:

<table>
  <tr>
    <td width="200" align="center"><strong>EU COMO... <code>PERSONA</code></strong></td>
    <td width="400" align="center"><strong>QUERO/PRECISO ... <code>FUNCIONALIDADE</code></strong></td>
    <td width="300" align="center"><strong>PARA ... <code>MOTIVO/VALOR</code></strong></td>
  </tr>
      <tr>
        <td>[NOME]</td>
        <td>[FUNCIONALIDADE]</td>
        <td>[MOTIVO]</td>
      </tr>
      <tr>
        <td>[NOME]</td>
        <td>[FUNCIONALIDADE]</td>
        <td>[MOTIVO]</td>
      </tr>
</table>

## Modelagem do Processo de Negócio 

### Análise da Situação Atual

// TODO

### Descrição Geral da Proposta

//TODO

### Processo 1 – As Is (Modelo atual - sem implementação da solução)

// TODO

### Processo 2 – To Be (Modelo ideal - pós implementação da solução)

// TODO

## Relação Potencialidades e Oportunidades de Melhoria para o Processo de Negócio

// TODO

## Indicadores de Desempenho

// TODO

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.
Para priorizar os requisitos, foi utilizado  a técnica de Escala de três Níveis, para essa técnica foi definido dois aspectos principais: importância e urgência.
Assim, forma-se um quadrante, que é usado para obter o nível de prioridade do requisito, como mostrado na figura a seguir:

// [IMAGEM]

### Requisitos Funcionais

<table>
  <tr>
    <td align="center" width="80">ID</td>
    <td align="center" width="800">Descrição do Requisito</td>
    <td align="center" width="100">Prioridade</td>
  </tr>
  <tr>
  <td align="center">RF-001</td>
    <td align="left">O Sistema deve permitir que o usuário crie uma conta.</td>
    <td align="center">ALTA</td>
  </tr>
    <tr>
    <td align="center">RF-002</td>
    <td align="left">O Sistema deve permitir que o usuário faça login em uma conta já cadastrada.</td>
    <td align="center">ALTA</td>
  </tr>
    <tr>
    <td align="center">RF-003</td>
    <td align="left">O Sistema deve permitir que o usuário recupere a senha de sua conta.</td>
    <td align="center">ALTA</td>
  </tr>
    <tr>
    <td align="center">RF-004</td>
    <td align="left">O Sistema deve listar todos os filmes em cartaz no cinema.</td>
    <td align="center">ALTA</td>
  </tr>
    <tr>
    <td align="center">RF-005</td>
    <td align="left">O Sistema deve informar os horários dos filmes.</td>
    <td align="center">ALTA</td>
  </tr>
    <tr>
    <td align="center">RF-006</td>
    <td align="left">O Sistema deve informar a disponibilidade de um filme.</td>
    <td align="center">ALTA</td>
  </tr>
    <tr>
    <td align="center">RF-007</td>
    <td align="left">O Sistema deve permitir que o usuário escolha quais assentos reservar durante a compra dos ingressos.</td>
    <td align="center">ALTA</td>
  </tr>
    <tr>
    <td align="center">RF-008</td>
    <td align="left">O Sistema deve permitir que o usuário desista da compra dos ingressos 1 hora antes do filme começar.</td>
    <td align="center">ALTA</td>
  </tr>
    <tr>
    <td align="center">RF-009</td>
    <td align="left">O Sistema deve permitir que o usuário escolha em qual sala do cinema deseja ver o filme.</td>
    <td align="center">ALTA</td>
  </tr>
    <tr>
    <td align="center">RF-010</td>
    <td align="left">O Sistema deve permitir que o usuário imprima os ingressos.  </td>
    <td align="center">ALTA</td>
  </tr>
</table>

### Requisitos não Funcionais

<table>
  <tr>
    <td align="center" width="100">ID</td>
    <td align="center" width="800">Descrição do Requisito</td>
    <td align="center" width="100">Prioridade</td>
  </tr>
  <tr>
    <td align="center">RNF-001</td>
    <td align="left">O Sistema deve notificar o usuário 30 min antes de seu filme começar.</td>
    <td align="center">ALTA</td>
  </tr>
  <tr>
    <td align="center">RNF-002</td>
    <td align="left">O Sistema deve listar separadamente filmes sem disponibilidade.</td>
    <td align="center">ALTA</td>
  </tr>
  <tr>
    <td align="center">RNF-003</td>
    <td align="left">O Sistema deve implementar um sistema de fila para a 
escolha dos assentos, não permitindo mais usuários do que 
assentos disponíveis.
</td>
    <td align="center">ALTA</td>
  </tr>
  <tr>
    <td align="center">RNF-004</td>
    <td align="left">O Sistema deve escalar horizontalmente caso necessário.</td>
    <td align="center">ALTA</td>
  </tr>
  <tr>
    <td align="center">RNF-005</td>
    <td align="left">O Sistema deve liberar os assentos caso um usuário desista 
de seu ingresso.</td>
    <td align="center">ALTA</td>
  </tr>
  <tr>
    <td align="center">RNF-006</td>
    <td align="left">O Sistema deve reservar os assentos temporariamente por 5 
min após a escolha dos assentos pelo usuário, liberando caso 
não seja efetuada a compra dos ingressos.</td>
    <td align="center">ALTA</td>
  </tr>
  <tr>
    <td align="center">RNF-007</td>
    <td align="left">O Sistema deve sugerir salas alternativas caso não haja 
disponibilidade na sala atual.</td>
    <td align="center">ALTA</td>
  </tr>
</table>

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| O projeto deverá ser feito apenas por integrantes do grupo |


## Diagrama de Casos de Uso

// TODO

# Matriz de Rastreabilidade

// TODO

# Gerenciamento de Projeto

// TODO

## Gerenciamento de Tempo

// TODO

## Gerenciamento de Equipe

// TODO

## Gestão de Orçamento

// TODO
