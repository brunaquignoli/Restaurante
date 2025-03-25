# Restaurante
Site de restaurante (teste de implementação utilizando front + back)

    POSSIBILIDADES >
Spring Boot + REST API:

back-end: Java + Spring Boot (API REST).

front-end: HTML, CSS e JS  (HTTP para dados).

possibilidade de: Java Servlets + JSP (sem API):

menor chance mas existente: React ou Vue.js no front para design.

    funcionamento:

código de restaurante que tenha todos os pratos e os preços, peça o endereço, conte o valor total e pergunte se o pagamento vai ser em dinheiro, cartão ou na hora, e confirme tudo, agradecendo pela compra ao final
exemplo
textos do sistema: 
	Olá! Você deseja fazer um pedido no restaurante "Super Bowl"!
	Nosso cardápio contém os seguintes pratos:
	prato 1 - Arroz, picanha, alface e tomate (39,90)
	prato 2 - Arroz, maminha, batata assada (34,90)
	prato 4 - Arroz, strogonoff de carne, batata palha (35,90)
	prato 6 - Hambúrguer de filé mignon de 200g, pão com gergelim, alface, tomate, maionese, cebola agridoce (27,90)
	(demais pratos ...)
	Por favor, insira os seguintes dados: nome, endereço, quantidade de pedidos, pedidos, método de pagamento (1 - dinheiro; 2 - cartão; 3 - pix) e momento de pagamento (0 - agora; 1 - na entrega)

entradas: 
	[nome]: Clara 
	[endereço]: rua desconhecida, num 25
	[quantidade de pedidos]: 4 pratos
	[pratos]: pedido 2, prato 4, prato 6, prato 6
	[pagamento]: 2
	[momento de pagamento]: 1
	
sistema:
	Certo! confirmação de pedido: Pedido para Clara, no endereço "Rua desconhecida, num 25", os seguintes pratos: 1 unidade do prato 2, 1 unidade do prato 4 e 2 unidades do prato 6, pagamento em cartão no momento da entrega
	o pedido está correto? confirme com "sim" ou "não".

cliente: 
	sim

sistema:
	Certo! obrigada por comprar conosco e volte sempre. Enviaremos seu pedido feito com muito amor e carinho!
	

main = SistemaRestaurante
classe = informacoesPedido

CLASSE  
SistemaRestaurante  

ATRIBUTOS  
- nome: String  
- endereco: String  
- quantidadeDePedidos: int  
- numeroDosPedidos: List<Integer>  
- tipoDePagamento: byte  
- momentoDePagamento: byte
- precoTotal: double  
- confirmacao: String  

MÉTODOS  
+ exibirMenu(): void  
+ fazerPedido(): void  
+ calcularTotal(): double  
+ exibirConfirmacao(): void  
+ processarPagamento(): void  
+ finalizarPedido(): void  

;;


{
    private String nome;
    private String endereco;
    private int quantidadeDePedidos;
    private int numeroDosPedidos;
    private byte tipoDePagamento;
    private byte momentoDePagamento;
    private double precoTotal;
    private String confirmacao;
    
    /** construtor: nao vai ter precoTotal
     * 
     * @param nome
     * @param endereco
     * @param quantidadeDePedidos
     * @param numeroDosPedidos
     * @param tipoDePagamento
     * @param momentoDePagamento
     * @param confirmacao
     */
    
    public informacoespedido
}
