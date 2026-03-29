# Atividade-2-UC11
Aluno: César Miguel

# Projeto: LeiloesTDSat

Este projeto tem o objetivo de cadastrar, vender e consultar produtos

primeiro, há uma tela para cadstrar os produtos, inserindo o nome e o valor, e depois destes dois campos serem preenchidos, você poderá clicar no botão de "Cadastrar" que o produto será cadastrado no sistema. No canto inferior direito, há um botão que levará para outra janela onde tem uma tabela que mostrar os dados de cada produto cadastrado (id, nome, valor e status). Nesta mesma tela, você pode vender o produto, preenchendo o campo de vender e ao lado do campo, clicar o botão de "Vender". por úlrimo, na parte mais de baixo desta tela, você tem o botão de "Sair", que fecha a janela e volta para ajanela de cadastro, e o botão de "Consultar Vendas", que atualiza a tabela

As tecnologias utilizadas foram o java para a criação do sistema e o MySQL para a acriação do banco de dados sql.

# Última atualização: 28/03/2026 > 2

O valor primitivo do valor do produto foi alterado no código java e no banco de dados sql. Agora o projeto java utiliza BigDecimal ao envés de Int, e o código do MySQL utiliza DECIMAL(10,2) ao envés de INT(11), além de que o código MySQL agora tem um procedure que serve para converter a coluna `valor` de produtos armazenados já existentes (INT(11) para DECIMAL(10, 2))