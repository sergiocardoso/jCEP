jCEP
====

Recupera informações como rua, bairro, cidade e estado fornecendo apenas o CEP

Exemplo de uso:

$('.cCEP').jCEP({
	cep : $('#cep').val(), //CEP A PROCURAR
	bairro : '.cBairro', //REFERENCIA JQUERY PARA ENTREGAR BAIRRO
	rua :'.cRua', //REFERENCIA JQUERY PARA ENTREGAR RUA
	estado : '.cEstado', //REFERENCIA JQUERY PARA ENTREGAR ESTADO
	cidade : '.cCidade' //REFERENCIA JQUERY PARA ENTREGAR CIDADE
});
