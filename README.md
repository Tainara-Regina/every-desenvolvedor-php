## Teste para Desenvolvedor PHP - Every
> Esse processo seletivo possui duas partes: a primeira um teste de lógica (esse que você está fazendo) e a segunda parte nós entraremos em contato para falar sobre você e sobre o teste. 

Através desse teste iremos avaliar os seguintes pontos técnicos:
- Sua organização de código
- Sua otimização de código
- Nomenclatura de classes e funções
- Lógica


## O teste

Desenvolva uma aplicação em PHP puro que possua as seguintes rotas:

- **GET** /ceps
> Essa URL deve retornar os últimos 10 CEPs.
- **GET** /ceps/{cepEspecifico}
> Essa URL deve retornar dados de um CEP específico no banco de dados.

Quando o CEP passando na url /ceps/{cepEspecifico} não existir, ele deve pesquisar em https://viacep.com.br/ e salvar essas informações no banco de dados para que na segunda requisição ele não precise fazer request para a viaCEP.

## Banco de dados

Utilize MySQL como banco de dados, a organização das tabelas fica a seu critério.

## Bibliotecas PHP (composer)

O uso de bibliotecas é liberado, o uso de *frameworks* não.

## Envio

Faça um fork desse repositório e commite seu teste, você pode fazer o pull ou passar a URL do repositório pra nós.

## Tempo

Após recebido esse teste, você possui 3 dias úteis para terminar.
