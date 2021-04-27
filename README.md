# ZipCode4Bind
Consulta de Cep para Bind4D

Exemplo:

#Inserção do Atributo [ComponentZipCode(zcNull)] conforme campos. Dessa forma, ao consultar o cep o componente ja sabe os campos que deve preencher.

#Atibuto SET

    [ComponentZipCode(zcCEP)]
    edCep: TEdit;

#Atributo GET

    [ComponentZipCode(zcLogradouro)]
    edEnde: TEdit;

    [ComponentZipCode(zcBairro)]
    edBair: TEdit;

    [ComponentZipCode(zcComplemento)]
    edComp: TEdit;

    [ComponentZipCode(zcCidade)]
    edCida: TEdit;

    [ComponentZipCode(zcEstado)]
    edEsta: TEdit;
