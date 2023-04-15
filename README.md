# desafio-busca-cep

<div>
Seu desafio é construir uma API REST de consulta de endereço e cálculo de frete para<br>
um determinado CEP. O contrato da API deve ser conforme especificado abaixo:<br>
POST v1/consulta-endereco<br>
REQUEST<br>
{<br>
"cep": "01001000"<br>
}<br>
RESPONSE HTTP 200<br>
{<br>
"cep": "01001-000",<br>
"rua": "Praça da Sé",<br>
"complemento": "lado ímpar",<br>
"bairro": "Sé",<br>
"cidade": "São Paulo",<br>
"estado": "SP",<br>
"frete": 7.85<br>
}<br>
Para a busca do endereço do CEP, você deve consultar a API VIA CEP, conforme a<br>
documentação https://viacep.com.br/. O valor do frete é fixo de acordo com as regiões<br>
do Brasil: Sudeste (R$ 7,85), Centro-Oeste (R$ 12,50), Nordeste (R$ 15,98), Sul (R$<br>
17,30) e Norte (R$ 20,83). O CEP é obrigatório e pode ser passado com ou sem máscara<br>
na entrada e se o CEP não for encontrado uma mensagem informativa deve ser retornada<br>
para o cliente.<br>
</div>


### Ferramentas/IDE
<br>
-InteliJ<br>
-Postman
