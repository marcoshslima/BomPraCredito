# BomPraCredito
Esse repositório será utilizado para publicar o teste técnico solicitado pela empresa Bom Crédito.
Este projeto será desenvolvido em C#, BDD - SpecFlow e Nunit cobrindo os seguintes cenário solicitado no teste:

Automatize um cenário de testes que acesse a nossa landing page de empréstimo pessoal em https://demo.bompracredito.com.br/emprestimo-pessoal e efetue um cadastro de um cliente

 Pontos importantes:

1) O teste deve se certificar a que as validações dos campos estão funcionando

2) O teste deverá considerar a massa de testes abaixo:
|Ocupação|Profissão|

|Assalariado|Desenhista|

|Empresário|Piscicultor|

|Estudante|Estudante|

Cada submissão deverá utilizar um CPF diferente, gerado automaticamente
3) O ultimo passo do cadastro está na url "https://demo.bompracredito.com.br/v2/cadastrobasico/endereco"

4) Após a submissão do cadastro, a página "https://demo.bompracredito.com.br/v2/resultado" precisa ser carregada

5) Após a carga da página "https://demo.bompracredito.com.br/v2/resultado", deverá ocorrer um redirect para a página "https://demo.bompracredito.com.br/v2/cadastrocompleto"
