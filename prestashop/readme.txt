***********
M�dulo PagSeguro para o PrestaShop
Este m�dulo tem por finalidade realizar transa��es de pagamentos entre sistema PrestaShop e o PagSeguro
Dispon�vel para as vers�es 1.5.2 e 1.5.3.1 do PrestaShop
***********

- Instala��o

	- Para instalar esse m�dulo no PrestaShop, v� at� a op��o M�dulos, na �rea administrativa, clique em Adicionar novo m�dulo e importe esse m�dulo compactado.
	- Nesse instante, o m�dulo foi adicionado ao seu sistema por�m n�o est� instalado(ativo). Voc� precisa acessar a categoria Pagamentos & Gateways, procurar pelo m�dulo PagSeguro e instal�-lo.
	- Pronto! A instala��o foi realizada e a partir de agora o m�dulo estar� dispon�vel como op��o de pagamento das compras realizadas em seu sistema.

- Configura��es

Ap�s instalado o m�dulo, � necess�rio que se fa�a algumas configura��es para que efetivamente seja poss�vel utilizar-se dele. Essas configura��es est�o dispon�veis na op��o Configurar do m�dulo.

	- email: E-mail cadastrado no PagSeguro
	- token: Token cadastrado no PagSeguro
	- url de redirecionamento: url utilizada para se fazer redirecionamento ap�s o cliente realizar a efetiva��o da compra no ambiente do PagSeguro. Pode ser uma url do pr�prio sistema ou uma outra qualquer de interesse do vendedor.
	- charset: codifica��o do sistema (ISO-8859-1 ou UTF-8)
	- log: diret�rio a partir da ra�z do sistema, onde se deseja criar o arquivo de log . Ex.: /logs/log_pagseguro.log
			
* NOTAS:
	
	- Certifique-se que o email e o token informados estejam relacionados a uma conta que possua o perfil de vendedor ou empresarial;
	- Certifique-se que tenha definido corretamente o charset de acordo com a codifica��o (ISO8859-1 ou UTF8) do seu sistema. Isso ir� prevenir que as transa��es gerem poss�veis erros ou quebras ou ainda que caracteres especiais possam ser apresentados de maneira diferente do habitual.
	