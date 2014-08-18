jCEP
====
Plugin para jQuery.<br>
Recupera informações como rua, bairro, cidade e estado fornecendo apenas o CEP.<br>
<br>
Exemplo de uso:<br>
<br>
$('.cCEP').jCEP({<br>
	cep : $('#cep').val(), //CEP A PROCURAR<br>
	bairro : '.cBairro', //REFERENCIA JQUERY PARA ENTREGAR BAIRRO<br>
	rua :'.cRua', //REFERENCIA JQUERY PARA ENTREGAR RUA<br>
	estado : '.cEstado', //REFERENCIA JQUERY PARA ENTREGAR ESTADO<br>
	cidade : '.cCidade' //REFERENCIA JQUERY PARA ENTREGAR CIDADE<br>
});<br>
