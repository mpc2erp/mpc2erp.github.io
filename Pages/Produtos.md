---
layout: default
---

##### Se ainda não conhece a estrutura de telas do sistema, clique em <a href="https://mpc2erp.github.io/Pages/Telas" target="_blank">Telas do Sistema MPC²-ERP</a>

# Cadastro de Produtos
 
O Cadastro de Produtos, é um dos cadastros mais complexos e mais importantes para o correto funcionamento de qualquer Sistema. Deve ser elaborado por alguém que tenha conhecimento do assunto, treinamento no uso do sistema e seus recursos e, ainda com planejamento de um padrão a ser seguido para cada tipo de produto cadastrado.
É o local onde serão cadastrados e parametrizados TODOS os produtos e serviços utilizados e/ou prestados pela empresa. Tudo que se compra, tudo que se vende, e, tudo que se produz, item a item.

Para poder conhecer o Cadastro de Produtos, antes devem ser estudaos / conhecidos os seguintes Cadastros (abra a página clicando no assunto desejado) :

<a href="https://mpc2erp.github.io/Pages/TipoProd" target="_blank">Tipo de Produtos</a> 

<a href="https://mpc2erp.github.io/Pages/GrupoProd" target="_blank">Grupos de Produtos</a> 

<a href="https://mpc2erp.github.io/Pages/Unidades" target="_blank">Unidades de Medida</a> 

<a href="https://mpc2erp.github.io/Pages/ClasFis" target="_blank">Classificações Fiscais e Exceções do ICMS por Classificação Fiscal e Estado</a> 

<a href="https://mpc2erp.github.io/Pages/ICMS_UF" target="_blank">ICMS por Estado</a> 

<a href="https://mpc2erp.github.io/Pages/TabPreco" target="_blank">Tabelas de Preços</a> 

<a href="https://mpc2erp.github.io/Pages/Fases" target="_blank">Fases da Produção</a> 

A tela do Cadastro de Produtos é dividida em 8 abas, sendo as rotineiras Pesquisa e Dados Básicos seguidas ainda das abas Unidades, Compra / Venda, Estoque, Compostos, Composição e Imagens.

##### Aba Pesquisa

![](Img/Produtos01-Pesquisa.jpg) 

Um produto pode ser localizado pelo Código Interno, Referência, Descrição, Tipo ou ainda pelo Grupo de Produtos

##### Aba Dados Básicos

![](Img/Produtos02-Cadastro.jpg) 

Na aba Dados básicos, quando se está cadastrando um novo produto : 
O Código do Produto, é uma informação numérica, sequencial, criada automaticamente pelo sistema cada vez que se inclui um novo produto. 
Já a Referência é um código da empresa, alfanumérico, que é digitado pelo usuário. O sistema não permite que dois produtos usem a mesma referência.

Uma vez definida a referência, é hora de definir o <a href="https://mpc2erp.github.io/Pages/TipoProd" target="_blank">Tipo do Produtos</a>, ou seja, é neste ponto que se define se o Produto em questão é uma Matéria Prima, Um Material de Consumo, Um Produto Acabado ou Intermediário (que será produzido pela empresa), se é um patrimônio, um serviço ou um serviço de terceiros, etc ... Todos os materias e serviços comprados, vendidos, revendidos ou produzidos devem ser cadastrados.

Na sequência, será definido o <a href="https://mpc2erp.github.io/Pages/GrupoProd" target="_blank">Grupos do Produtos</a>. Este Grupo do Produto é uma sub-categoria, que permite melhor setorização / divisão dos materiais, dentro de um Tipo. Por exemplo, em uma indústria de Alimentos, pode-se criar um grupo Farinhas Secas, Fermentos, Ingredientes Líquidos, etc ... Essa divisão ou não, fica a cargo da empresa

Após digitar a Descrição e os Detalhes do Produto, deve-se definir a Unidade de Inventário. A Unidade de inventário tem obrigatóriamente que estar cadastrada no <a href="https://mpc2erp.github.io/Pages/Unidades" target="_blank">Cadastro de Unidades de Medida</a>. É importante que seja selecionada com critério, pois, a pesar do sistema permitir operações com qualquer outras unidades relacionadas (Aba unidades), a Unidade de Inventário é considerada como principal, e os relatórios sempre tratam as informações a partir dela.

Código EAN e Código DUM-14 são os códigos de barras da Unidade e da Embalagem. Só deve ser preenchida quando a empresa utilizar essa informação em seus produtos, pois esse código é validado na(s) NF-e(s).

A <a href="https://mpc2erp.github.io/Pages/ClasFis" target="_blank">Classificação Fiscal</a> deve ser preenchida sempre com acompanhamento e anuência da Contabilidade, pois influenciam diretamente na tributação dos produtos.

Definida a Classificação Fiscal, é hora de definir a Origem do Produto, seguindo a tabela apresentada, que é fornecida pela SEFAZ.

Ainda nessa aba, na parte de baixo, sáo apresentadas duas informações importante. Quem cadastrou o produto, e caso ele tenha sido alterado, que foi o usuário que fez essa alteração.

##### Lembrando qeu todas as alterações ficam registradas como eram anteriormente, como ficaram e quem alterou, de acorso com parametrização realizada pela MPC² Sistemas.

##### Aba Unidades

![](Img/Produtos03-Unidades.jpg) 

A Aba Unidades deve ser manipulada com conhecimento do que se está fazendo. Uma relação entre unidades cadastrada errada, pode comprometer seu inventário apresentando ao Fisco, uma informação não condizente com a realidade.
Todas as unidades que se desejar relacionar, tem obrigatóriamente que estar cadastrada no <a href="https://mpc2erp.github.io/Pages/Unidades" target="_blank">Cadastro de Unidades de Medida</a>.
Para inserir novas unidades, basta clicar no ícone de + abaixo da tabela, informar qual é a unidade a ser inserida, e Qual q Relação entre ela e a outra unidade, podento ser a de inventário ou qualquer outra já relacionada.

![](Img/Produtos03-Unidades_2.jpg) 

Nessa tela, nos Flag´s do lado esquerdo, informamos se essa relação está ativa, se essa unidade que está sendo incluída pode ser utilizada com Compra e/ou para Vendas desse material, e ainda se essa é a Unidade Tributável do Produto. Nos Flag´s do lado direito, observamos (não é possível alterar aqui) se essa é a Unidade de Inventário, se ela é a unidade padrão para Compras e/ou se é a unidade padrão para Vendas. Para quem usa, qual o código DUN-14 dessa unidade.
Podemos incluir informações de Altura, Larura e Comprimento, se for o caso, mas o principal ... A relação entre as unidades. No exemplo, uma Bomba de 100 litros equivale a 100 litros do produto.

![](Img/Produtos03-Unidades_3.jpg) 

Nesse exemplo, o Produto Thiner, tem como unidade principal o Litro, mas pode sem comprada em Lata de 1 litro, lata de 15 litros, bombona de 100 litros ou bombona de 200 litros, mas ela é utilizada nas formulações da empresa, em Quilos !! E um Kg de Thiner corresponde a 1,38313 Litros.

Uma particularidade do MPC²-ERP na parte de Unidades, é que quando uma unidade é relacionada, o sistema cria Automaticamente TODAS as relações possíveis entre TODAS as unidades. 

![](Img/Produtos03-Unidades_4.jpg) 

Isso não fica exposto por poder parecer complexo para os usuários, mas se clicar em Exibir Todas as Relações, na tabela de baixo da aba, são exibidas todas as relações possíveis entre as unidades, por exemplo, ao incluir a unidade KG, informamos que 1 KG equivale a 1,38313 Lts. Automaticamente o sistema já calculou que 1 litro pesa 0,723 (arredondando) Kg.

Até o momento não conhecemos outro sistema com esta inteligência !

##### Aba Compra / Venda

![](Img/Produtos04-Compra_Venda.jpg) 

As funcionalidsades desta aba, são importantes e demandam atenção. Na parte de cima, estão as informações de Compras do Produto, para os casos em que o produto em questão é adquirido no mercado (MP / MC / Revenda / Etc ...). As informações definidas são: 
 - Unidade Padrão para Compras : Pode ser qualquer uma das unidades definidas na Aba Unidades, que estejam marcadas como Unidade para Compra. O Padrão é estabelecido para simplificar as compras, pois nos Pedidos de Compra, a unidade padrão para Compras de cada ítem é oferecida. Porém, é uma mera SUGESTÃO, podendo ser utilizada qualquer uma das unidades listadas.
 - Preço Padrão de Compra (Por UN): Este valor é definido manualmente, como referência, enquanto não há compras para o produto.
 - Ao clicar no botão Fornecedores, é apresentada uma tela com a tabela dos fornecedores que já venderam o produto em questão.
 
 ![](Img/Produtos04-Compra_Venda_1.jpg) 

- Clicando no botão Compras, o sistema abre uma tela com o histórico de compras desse produto.

![](Img/Produtos04-Compra_Venda_2.jpg) 

Na parte de baixo da tela, ficam as informações referentes a venda do produto em questão, para os produtos de Venda (Produção Própria) ou Revenda. Nesta parte, são digitadas as seguintes informações:
- Unidade Padrão para Vendas: Usando a mesma filosofia de Compras, aqui se define qual é a Unidade Padrão para Vendas. E, assim como em compras, trata de uma sugestão, podendo vender nas unidades listadas, marcadas como Unidade de Venda.
- Preço Básico de Venda (por UN): Esse é o preço ustilizado como Base para as <a href="https://mpc2erp.github.io/Pages/TabPreco" target="_blank">Tabelas de Preços</a> que utilizam porcentagem. Esse assunto deve ser cuidadosamente estudado e compreendido para um bom funcionamento.
- Quantidade Padrão de Venda: Essa informação atende empresas que não querem cadastrar outras unidades. Por exemplo, a unidade é PC, mas só vendo de cento e não quero trabalhar com a unidade CENTO ... Coloco a Quantidade Padrão como 100.
- Sua contabilidade deve fornecer uma tabela com quais estados exigem o FCP e qual a alíquota para aquele estado, e O Flag Contribui com o FCP (Fundo de Combate à Pobreza) é uma informação que 
- Clicando no botão Preços, é apresentada uma tabela com Todas as Tabelas de Preços que permitem usar este produto. Para entender as informações apresentadas nesta tabela, é necessário ler e entender detalhadamente o funcionamento das <a href="https://mpc2erp.github.io/Pages/TabPreco" target="_blank">Tabelas de Preços</a>

![](Img/Produtos04-Compra_Venda_3.jpg)

- Quando clica no Botão Pedidos, o sistema oferece uma tabela com os Pedido de Venda que tem este produto, permitindo ao usuário ampla visão dos cenários de venda do produto. 

![](Img/Produtos04-Compra_Venda_4.jpg)

##### Aba Estoque

![](Img/Produtos05-Estoque.jpg) 

As informações desta Aba, configuram como o Estoque deste Produto deve ser tratado na empresa, parametrizando / informando os seguintes dados :

   - Flag Controla Estoque: 

Nesta aba, ainda pede ser definido:

   - Tipo de Título padrão: Boleto, Cartão, etc ...
   - Parâmetros para CNAB
   Os Padrões para CNAB como taxa de multa e alíquota de juros mês e se protesta ou não e em quanto tempo, são definidos no Cadastro de Contas correntes. Aqui no cadastro de Clientes, pode-se estabelecer exceções para os padrões. Repare que por defalult, o cadastro do Cliente vem com os Flags Segue Padrão para juros e multa e Segue Padrão para protesto marcados. Isso indica que devem ser utilizados os valores definidos como padrão, no Cadastro de Contas Correntes. Porém, se for interesse da empresa dar uma tratativa especial para um determinado Cliente por ser muito bom ou muito ruim, basta desmarcar o Flag de Segue Padrão, e determinar os valores que serão usados especificamente para este Cliente.
   
##### Aba Entrega 

![](Img/Produtos05-Estoque.jpg) 
   
Assim como na aba Faturamento, a primeira informação que encontramos é a Origem do Endereço do endereço de Cobrança, que pode ser Cadastral (Opção Padrão), que traz o endereço do cadastro definido na aba de Dados Básicos, Grupo, que traz o endereço da matriz do grupo, indicado na aba de Dados Básicos, ou Outro, que abre os campos para digitação.
Nesta aba, ainda pede ser definido:

   - Padrão para Modalidade do Frete: Sugere quem é o Pagador padrão
   - Região de Entrega: O Cadastro da Região de Entrega é um facilitador para distribuição de carga.
   - Transportadora: Indica qual a Transportadora Padrão deste Cliente.
   - Obs. para entrega: Dados internos de observações pertinentes à entrega

##### Aba Observações

![](Img/Cliente08.jpg) 

Local destinado à observações internas sobre o cliente. Estas informações não circulam em pedidos, notas, etc ... Sendo apenas para referência interna, do tipo "Vencimentos apenas nas sextas-feiras", "Só recebem mercadorias nas quitas-feiras" e assim por diante.

##### Aba Contatos

![](Img/Cliente09.jpg) 

Na aba contatos são gerenciados os doncatos dentro do cliente, não havendo limite para o número de contatos.

##### Aba Produtos

![](Img/Cliente10.jpg) 

Nesta aba são apresentados todos os produtos que já foram negociados com este cliente, incluindo valores e quantidades.

