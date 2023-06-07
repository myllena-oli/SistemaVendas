# SistemaVendas
`Classe Cliente:` Nessa classe foi colocado todos atributos necessários para um cliente, e foram criados os Maps cpfCliente e emailCliente que relacionam 
os clientes aos seus cpf e email para que cada cliente tenha cpf e emails diferentes. Foi criado uma lista de clientes e todos os métodos que envolvem clientes: 
listarClientes, cadastrarCliente, login, e todos os gets e sets necessários.

`Classe Vendedor: ` Nessa classe foi colocado todos atributos necessários para o vendedor e todos os métodos relacionados com produto, como: adicionarVendedor,
listarVendedores, CadastrarVendedor, e todos os gets e sets necessários.

`Classe Produto:` Nessa classe foi colocado todos atributos necessários para o produto e todos os métodos relacionados com produto, como: buscarProdutoPorCodigo, listarProdutosDisponíveis,
adicionarProduto, e todos os gets e sets necessários.

`Classe Venda: ` Nessa classe foi colocado todos atributos necessários para a venda e todos os métodos relacionados com produto, como: listarVendas, realizarVenda, pesquisarCompraCliente,
PesquisarCompraVendedor, obterDiaAtual, e todos os gets e sets necessários.

`Classe ComprasProdutos:` Essa classe é uma classe do tipo genérico que foi feita para que eu possa criar estâncias que relacionam um valor à uma chave. Escolhi criar
essa classe ao invés de usar outro Map, pois dessa forma as chaves podem se repetir, o que faz sentido pois eu queria que o cliente pudesse comprar a mesma coisa mais
de uma vez.

`Classe IniciarLoja:` Nessa classe foi criado o método main, onde há alguns vendedores, clientes e produtos pré-cadastrados, além de ser o lugar onde eu construí o menu
para ser inicializado e chamado todos os métodos necessários.

`Classe LimiteDeTentativasException:` Foi criada um tipo de exceção, onde a pessoa só pode tentar digitar a senha 3 vezes.





