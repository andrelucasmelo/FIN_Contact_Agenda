# FIN_Contact_Agenda
## Classes do Código
### Classe Pessoa

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

### Classe Empresa

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
