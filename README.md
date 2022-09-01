## Challenge de Data Science (2022)
Somos uma equipe de dados que foi contratada para fazer parte do banco digital internacional chamado Alura Cash. No primeiro dia, a diretoria financeira nos convocou para uma reunião para informar que, recorrentemente, estão surgindo pessoas inadimplentes após a liberação de créditos.

Por conta disso, foi solicitada uma solução para diminuir as perdas financeiras geradas por pessoas mutuárias que não quitam suas dívidas. Nos foi informado também que teríamos o prazo de um mês para encontrar essa solução e apresentá-la à diretoria financeira. Sendo assim, solicitamos um conjunto de dados contendo as informações de clientes, da solicitação de empréstimo, do histórico de crédito, bem como se a pessoa mutuária é inadimplente ou não.

## Semana 1
A semana 1 é dedicada à análise e estruturação dos dados oferecidos pelo banco com MySQL. Primeiro, foi notado que os dados estavam diferentes dos usuais, pois sua fonte era um dump, o que nos exigiu uma atenção especial na manipulação deles. Assim, buscamos ler todo o registro para entender nossos dados. Notamos que os valores estavam divididos por tabelas características, com valores de ID referenciando os dados de cada cliente.

Então, iniciamos analisando as informações que o conjunto de dados possuía. Observamos que os dados estavam em inglês, os valores de texto estavam sem padronização, além de vários valores nulos.

Foi percebida também a existência de uma tabela que continha a relação de todos os IDs de uma mesma pessoa cliente do Alura Cash. Dessa forma, o primeiro passo foi tratar nossos dados para deixá-los padronizados no texto, bem como, corrigir inconsistências relacionadas ao tipo e estruturação deles.

Depois buscamos unir as tabelas pelos valores de IDs que eram correspondentes entre si, deixando todos os dados em uma única tabela de dados de clientes. Após uma conversa entre a equipe, decidimos não eliminar os valores nulos dentro do banco de dados, pois poderiam conter informações de clientes que são importantes para o banco.

A tabela de dados unidos foi exportada do MySQL como csv e será utilizada nas próximas semanas.

### Atividades realizadas (Semana 1)
- [X] Instalar MySQL Workbench e importar **database dump**.
- [X] Analisar quais os tipos de dados.
- [X] Verificar quais são as inconsistências nos dados.
- [X] Entender quais informações o conjunto de dados possui.
- [X] Verificar quais são as inconsistências nos dados.
- [ ] Corrigir as inconsistências nos dados.
- [ ] Unir as tabelas de dados de acordo com os IDs.
- [X] Traduzir as colunas.
- [ ] Exportar a tabela de dados unidos como csv.