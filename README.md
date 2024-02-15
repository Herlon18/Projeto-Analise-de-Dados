# Projeto Analise de Dados - Python / Google Colab

Projeto do mini curso de Análise de Dados da Hashtag em Python utilizando o Google Colab

Projeto realizado com banco de dados de cartões de créditos com
proposito de descobrir a causa da maior parte dos cancelamentos dos clientes.
Inicialmente importando a ferramenta pandas para realizar o tratamento
dos dados.

Finalizando com o potly.express e plotly.graph_objects para uma melhor visualização com gráficos.
Realizei o projeto com base no acompanhamento no minicurso, porém, para finalizar adicionei varios outros elementos
para que o projeto fique realmente do jeito que eu gostaria.

# Informações retiradas da análise

## Segue Gráficos Principais Analisados

<img src="/img/Ativos e Cancelados.png">

<img src="/img/Categoria do Cartão.png">

<img src="/img/Contato.png">

<img src="/img/Limite Consumido.png">

<img src="/img/Produtos Contratados.png">

<img src="/img/Qtd de Transações.png">

<img src="/img/Valor de Transações.png">

### Clientes Ativos - 8499

### Cancelados - 1627

## Informações retiradas da análise de dados inicial.

- A maior parte dos Clientes estão na Categoria Blue, consequentemente a
maior parte de cancelados também, então o foco inicial seria nos clientes da
categoria Blue.

- Quanto mais produtos contratados um cliente tem, menor a
chance de ele cancelar.

- Quanto mais transações e quanto maior o valor das transações, menor
a chance de ele cancelar.

- Quanto maior a quantidade de contatos que o cliente teve que fazer,
maior a chance de ele cancelar.

# Conclusão:

Principal motivo dos cancelamentos seria provavelmente por 
problemas não resolvidos ou recorrentes, tendo em base a análise do 
gráfico de contatos.
A maior parte dos cancelamentos ocorrem a partir do Terceiro contato do 
cliente, subindo cada vez mais.

- ### 2º Contato – Taxa de cancelamento = 12.5%
  <img src="/img/2 contato.png">

- ### 3º Contato – Taxa de cancelamento = 20.2%
  <img src="/img/3 contato.png">
  
- ### 4º Contato – Taxa de cancelamento = 22.6%
  <img src="/img/4 contato.png">
  
- ### 5º Contato – Taxa de cancelamento = 33.5%
  <img src="/img/5 contato.png">

- ### 6º Contato – Taxa de cancelamento = 100%
  <img src="/img/6 contato.png">
  
### (Todos os clientes que entraram em contato na 6ª vez realizaram o cancelamento)

# Sugestão:

De acordo com dados retirados, uma das opções a ser tomada 
seria fazer algo incentivando os clientes utilizarem mais os cartões e 
ter facilidades para ter outros produtos contratados junto com os 
cartões, pois em relação as informações iniciais, isso reduziria as 
chances do cliente realizar o cancelamento posteriormente.


É necessário também verificar com a central de atendimento referente 
aos contatos, verificando o motivo principal pelo qual o cliente entra 
em contato, para que possa estar resolvendo da melhor maneira possível, 
não permitindo o mesmo a retornar o contato várias vezes.


