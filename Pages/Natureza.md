---
layout: default
---

##### Se ainda não conhece a estrutura de telas do sistema, clique em <a href="https://mpc2erp.github.io/Pages/Telas" target="_blank">Telas do Sistema MPC²-ERP</a>


# Cadastro de Naturezas de Operações
 
###### Esta funcionalidade é acionada na Opção Cadastros do Menu Principal, no Sub-Menu Fiscal

O cadastro de Naturezas de Operação é chave para o bom funcionamento de pedidos de vendas e emissão de notas fiscais, pois é a partir dele que se configura como as situações de cada operação devem se comportar.

É necessário conhecimento dos conceitos tributários envolvidos para que se trabalhe de maneira correta com as informações contidas em cada Natureza de Operação.
Recomendamos que seja acompanhado pelo(s) profissional(ais) do depatamento contábil ou escritório de contabilidade

![](Img/Natureza01.jpg) 

Uma Natureza de Operação está sempre ligada a uma CFOP e tudo que ela representa. Porém pode-se ter mais de uma Natureza de Operação por CFOP.
Ao clicar no ícone de lupa que fica ao lado do Código da CFOP, será apresentada a tabela das CFOP´s.
Repare no exemplo abaixo, usado para vendas de produção própria dentro do estado, como está o cadastrado e o que representa cada informação.

![](Img/Natureza02.jpg) 
   
A Operação (venda, remessa, etc ...) segue aquilo que está parametrizado na Natureza para calcular os tributos e também as informações adicionais das notas fiscais.

![](Img/Natureza03.jpg) 

Os Flags que podem ou devem ser alterados
   - Ativa : indica se a Natureza está liberada para ser utilizada
   - Respeita Exceções: indica se a tributação segue ou não as eventuais exceções que podem estar definidas em outros cadastros.
   - Gera Cobrança: indica se a Operação deve gerar títulos financeiros ou não
   - Movimenta Estoque: indica se os movimentos realizados com esta natureza movimentam o(s) estoque(s) dos produtos
   - Pedidos de Venda: Indica se a Natureza pode ser utilizada em Pedidos de Venda
   - Padrão para Ped. Vendas: indica se é uma Natureza padrão para Vendas

São Flags meramente informativos:
   - Incide ICMS: definido pela CST do ICMS
   - Incide IPI: definido pela CST do IPI
   - Substituição Tributária: definido pela CFOP e CST do ICMS
   - Venda: definido pela CFOP

![](Img/Natureza04.jpg) 

Para cada Natureza da Operaçãos, podem ser devinidos os seguintes códigos:
   - CST do ICMS: define o Comportamento básico para o cálculo do ICMS
   - Se há desoneração do ICMS e caso haja, qual o Motivo da Desoneração
   - CSOSN (Código da Operação para empresas do Simples). O Código SOSN é digitado para contemplar uma obrigação fiscal, porém não influencia nos cálculos dos tributos, sendo obrigatório para o Sistema que a CST do ICMS seja preenchida, independente do regime tributário da empresa, pois é a partir dela que se realizam os cáluclos do ICMS. Veja no fim da página a tabela de correlação entre as CST's e as CSOSN's.
   - CST do IPI: define o comportamento básico para o IPI
   - Código do Enquadramento do IPI: Local para definição do Enquadramento do IPI. 
   - CST do COFINS: define o comportamento básico para o COFINS
   - CST do PIS: define o comportamento básico para o PIS

As regras definidas no cadastro de Naturezas de Operação são passíveis de exceções. 
As exceções são normalmente definidas no cadastro das Classificações Fiscais. 

Conheça mais sobre as Classificações Fiscais clicando em <a href="https://mpc2erp.github.io/Pages/ClasFis" target="_blank">Classificações Fiscais</a>

Nota Importante: As alterações das configurações tributárias NÃO alteram os documentos gerados anteriormente à mudança, e sim, apenas os novos documentos.

Para o bom funcionamento de um sistema, é imprescindível que as informações dos cadastros sejam de boa qualidade.
### Crie o hábito de realizar revisões periódicas nos seus cadastros.
##### As alterações nesse cadastro podem ser auditadas, pois é gerado um log para elas. 









