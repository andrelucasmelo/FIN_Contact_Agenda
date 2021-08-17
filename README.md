# FIN Python - Contact Agenda

Esse é um projeto de teste, feito para expandir as habilidades de programação e tambem como passatempo para os projetos do dia a dia. A finalidade deste projeto é servir como uma Aplicação de Agenda, em Backend, possibilitando a interação através de API REST para consulta, inclusão, exclusão e edição de contatos.

Esta agenda deve ser separada em alguns objetos principais que serão descritos como classes com seus métodos e atributos.

## Classe Pessoa

#### Atributos:
- Nome (str)
- Endereço (list Class Endereço()) 
- Telefone (list Class Telefone()) 
- E-mail (list Class Email()) 
- Rede Social (list Class SocialNetWork()) 
- Data Nascimento (str)

#### Metodos:
- getPessoa - Retorna os dados de uma pessoa, consultados por parametro genérico, Id, nome, email ou rede social.
- setPessoa - Altera uma pessoa em especifico através do seu Id.
- newPessoa - Cria uma nova pessoa, retornando seus dados.
- removePessoa - Remove uma pessoa com base no seu Id.

## Classe Empresa

#### Atributos:
- Nome (str)
- Endereço (list Class Endereço()) 
- Telefone (list Class Telefone()) 
- E-mail (list Class Email()) 
- Rede Social (list Class SocialNetWork()) 
- CNPJ (str)
- Area (list Class Area())

#### Metodos:
- getEmpresa - Retorna os dados de uma pessoa, consultados por parametro genérico, id, CNPJ, nome, email ou rede social.
- setEmpresa - Altera uma pessoa em especifico através do seu Id.
- newEmpresa - Cria uma nova pessoa, retornando seus dados.
- removeEmpresa - Remove uma pessoa com base no seu Id.
