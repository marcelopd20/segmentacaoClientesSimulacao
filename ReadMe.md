### Simulação de SEGMENTAÇÃO DE CLIENTES

O Presente estudo traz uma metodologia de segmentação de clientes, utilizando um conjunto de dados com tamanho amostral de 2000 ocorrências, com dados fictícios simulando dados anônimos de clientes, de forma a proteger a privacidade dos usuários. Assim buscamos simulanr uma coleta de dados que poderia ser realizada pelo consentimento do cliente ao aderir o uso da poupança, através de termo de consentimento de compartilhamento de dados.  


#### DESCRIÇÃO DAS VARIÁVEIS
**ID**: Apresenta o ID do cliente, Primary Key.

**Sex Biological**: Gênero dos clientes. 
0 - Masculino.
1 - Feminino.

**Marital status**: Estado Civil do Cliente.
0 - Solteiro
1 - Não Solteiro

**Age**: Idade do Cliente, pode ser obtido pela Data atual subtraindo data de nascimento, utilizando biblioteca datetime. (Inteiro)


**Education**: Escolaridade do Cliente
0 - Ensino Médio Incompleto
1 - Ensino Médio Completo
2 - Graduação Incompleta
3 - Graduado

**SavAcBal**: Saldo Pontual da Poupança (Inteiro)


**Occupation**: Ocupação
0 - Desempregado 
1 - Empregado
2 - Autonomo

**Settlement size**: Tamanho da cidade
0 - Cidade Pequena
1 - Cidade Médio Porte
2 - Cidade de Porte Grande

Esta análise explora dados simulados para segmentação de clientes, de forma a contribuir com a teoria de dados que guiem as decisões, utilizando método de clusterização com K-means, disponível na biblioteca sklearn do Python.


A segmentação utilizando aprendizagem de máquina não supervisionada ajuda-nos a enteder de maneira simples diferentes grupos presentes na população apresentada, e assim guiar ações de marketing para públicos específicos, pensando em comunicação direcionada e estratégias que visam o sucesso do cliente.

Os dados e o tutorial foi adquirido no [LINK](https://www.kaggle.com/code/gustavogodinho/segmenta-o-de-clientes/notebook)
