# Telecom Customer Churn

## Contexto

Imagine que voce e um dono de uma empresa de assinaturas e que está percebendo que com forme os anos passam alguns clientes estão deixando a empresa, e como e uma coisa muito repentina, voce não consegue tomar uma decisão ou sua decisão não surge tanto efeito, pois o cliente já desistiu do produto, em busca de evitar que isso continue ocorrendo, voce resolver contratar uma consultoria de Ciencia de dados, para que a pessoa em pose dos dados da sua empresa consiga de alguma forma, identificar os principais fatores que fazem o cliente desistir de um produto e por fim prever se o cliente e um potencial churn ou não, voce acredita que com isso voce vai poder saber antes que aconteça e assim já começar de cedo alguma campanha para previnir que isso aconteça, assim fazendo a empresa perder menos clientes e dinhiero, depois de uma conversa com o cientista e ele entedendo bem o problema que voce está passando e entendo bem o que voce quer de solução, ele inicia o projeto...

## Definições:
Churn é uma metrica que indica o quanto a sua empresa perdeu de receita ou clientes, por isso quando.


## Objetivo do projeto:
O objetivo do projeto, assim como destacado acima e descobrir se o cliente vai ser churn ou não e também descobrir os principais fatores que fazem ele ser churn, ou seja, as features(colunas) dos dados.


## Considerações finais e Expectativas para o projeto:

Esse projeto veio da plataforma Keggle, nessa plataforma temos acesso a diversos datasets(dados) e desafios desse projeto, nesse dataset em especifico, não havia nenhuma especifição do objetivo a ser alcançado e nem mesmo o objetido do projeto e para o que ele iria ser usado, então eu espero que consiga desenvolver um modelo que tenha 80% de acúracidade(essa e a minha meta) e uma Classe que consiga aplicar o modelo em qualquer tipo de dados desde que tenham a mesmas colunas.


![image](https://user-images.githubusercontent.com/92899088/182632586-ce402b7b-239a-4692-8d90-423fe2a0bf8e.png)



## Planejamento de Solução:
Como vou resolver o projeto? O que eu espero ter no fim? Quais ferramentas eu vou usar?

O que eu espero ter no fim do projeto?
Bem, assim como destacado acima o meu objetivo e ter:
  - Modelo com 80% de acuracidade ou mais
  - Uma classe que consiga pegar os dados, seja qual for(desde que tenha as mesmas colunas) e consiga aplicar todas as transformações e realizar a previsão
  
 Quais ferramentas eu vo usar?
 Para resolver esse problema, eu vou utilizar as seguientes ferramentas:
 
  - Python: Fazer todo o processo de Limpeza, Transformação e Previsão.
  - Jupyter Notebook: IDe usada para usar a linguagem python de uma forma mais facil
  - Git and Github: Vou usar essas duas ferramentas para ir salvando o progresso do projeto em cada etapa.
  
  
Como vou resolver esse problema?
Para resolver um problema assim e necessario conhecer bem os dados e realizar análises mais gerais para saber se os dados são uteis para resolver o problema, para isso eu vou realizar 1 ciclo de realização do projeto, cada ciclo tem no minimo 10 etapas, acima voce pode ver os arquivos desse primerio ciclo, embora seja uma consideralvel quantidade de arquivos esse e a penas um ciclo, faço isso com o intuinto de conseguir entregar valor no tempo mais rápido possivel e já de cara indentificar problemas nos dados ou dados vão servir ou não.



## Validação das Hipoteses
Em busca de conhecer mais os dados e também aprender mais sobre o problema de negócio, eu inventei algumas hipoteses de negócio que a equipe da empresa poderia ter, claro qeu são mais simples e que com certeza os dados estariam em um melhor estado ou eu teria a possibilidade de buscar mais dados para responder mais perguntas.



H1: Clientes com mais de 30 meses na base são 30% dos meus clientes churn.
FALSA: Clientes com mais de 30 meses SÃO 85% DOS MEUS CLIENTES CHURN.

![image](https://user-images.githubusercontent.com/92899088/182637683-fe74fe0d-7a12-4805-8a56-b871fc787ccb.png)


H2: Clientes com income maior ou igual a 4 são 30% mais churn do que os outros clientes.
VARDADEIRA: Clientes com income maior ou igual a 4 são 87% MAIS CHURN DO QUE OS OUTROS CLIENTES.

![image](https://user-images.githubusercontent.com/92899088/182637910-9de395a3-9986-430b-b109-d7ed46ed97f1.png)

H3: Cliente com dias de eqpdays maior ou igual a 1000 são 40% churn que os outros.
FALSA: Clientes com eqpdays maior de 1000 REPRESENTAM MENOS DE 4% DOS MEUS CLIENTES CHURN.

![image](https://user-images.githubusercontent.com/92899088/182638055-3ac0b816-da50-4fd3-8e50-894510eb1910.png)


H4: Clientes com credito aprovado são 30% ou mais churn que os outros clientes.
VERDADEIRA: Clientes com credito aprovado são 104% MAIS CHURN DOS QUE OS CLIENTES SEM CRÉDITO APROVADO.

![image](https://user-images.githubusercontent.com/92899088/182638175-7c18da30-1600-4304-a70c-479aa5c500b1.png)

H5: Clientes com mais de 4 pessoas adultas na familia são 30% mais churn do que os outros.
FALSA: Clientes com mais de 4 pessoas na fámilia são 79% MENOS CHURN do que os outros clientes

![image](https://user-images.githubusercontent.com/92899088/182638327-b16f8283-6c28-4a0a-9f02-6a1d9a975849.png)


## Resultados Financeiros
Para realizar essa análise de perde ou ganho financeiro, eu usei uma coluna chama de **Income** dos dados, essa coluna continua valores encondados por exemplo: 0.7, 0.5...por isso eu considerei que esse era o valor do cliente para a empresa, com base necessa informação eu fiz uma análise de quanto a empresa deixar de perder caso o modelo acertasse e quanto ela iria perder quando o modelo errasse

abaixo contém a foto d análise e a minah interpretação, está resumido acima mas eu descidir trazer mais detalhada para que voce possa entender o que estava passando na minha cabeça quando eu fiz isso, assim podendo concorda ou dicosdar.

!![image](https://user-images.githubusercontent.com/92899088/182639346-0a6bd5dd-ad6a-4b0b-acc9-1b0c645a5216.png)


## Perfomance do modelo
Abaixo vou deixar as imagens da perfomance do modelo, também vou deixar uma análise financeiro que usei seguindo o mesmo criterio do resultado financerio acima, porém vou deixar a explicação também!


- Perfomance:
![image](https://user-images.githubusercontent.com/92899088/182639983-6ec34d9d-945f-43a8-9009-61ad0153fa14.png)

- análise financeira do erro do modelo:
![image](https://user-images.githubusercontent.com/92899088/182640171-24142e5e-3844-4fc7-a231-f6020654cc7c.png)

- Real vs Previsto
![image](https://user-images.githubusercontent.com/92899088/182640341-71461e70-12fd-4237-a4ab-58b9cedf3106.png)


## Conclusão Final:










