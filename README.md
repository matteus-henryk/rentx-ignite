## Cadastro de carro

**Requisitos funcionais**
Deve ser possivel cadastrar um novo carro.

**Regra de negócio**
Não deve ser possivel cadastrar um carro com uma placa já existente.
O carro deve ser cadastrado com a disponibilidade por padrão.
* O usuario responsavel pelo cadastro deve ser um usuario administrador.


## Listagem de carros

**Requisitos funcionais**
Deve ser possivel listar todos os carros disponiveis.
Deve ser possivel listar todos os carros disponiveis pela categoria. 
Deve ser possivel listar todos os carros disponiveis pelo nome do carro. 
Deve ser possivel listar todos os carros disponiveis pelo nome da marca. 

**Regra de negócio**
O usuario não precisa estar logado no sistema .


## Cadastro de Especificação no carro

**Requisitos funcionais**
Deve ser possivel cadastrar uma especificação para um carro.
Deve ser possivel listar todas as especificações.
Deve ser possivel listar todos os carros.

**Regra de negócio**
Não deve ser possivel cadastrar uma especificação para um carro não cadastrado.
Não deve ser possivel cadastrar uma e specificação já existente para um mesmo carro.
O usuario responsavel pelo cadastro deve ser um usuario administrador.

## Cadastro de imagens do carro

**Requisitos funcionais**
Deve ser possivel cadastrar a imagem do carro.
Deve ser possivel listar todos os carros.

**Requisitos não funcionais**
Utilizar o multer para upload de arquivos.

**Regra de negócio**
O usuário deve poder cadastrar mais de uma imagem pera o mesmo carro.
O usuario responsavel pelo cadastro deve ser um usuario administrador.


## Aluguel de carro

**Requisitos funcionais**
Deve ser possivel cadastrar um aluguel.

**Regra de negócio**
O aluguel deve ter duração minima de 24h hora.
Não deve ser possivel cadastrar um novo aluguel caso já exista um aberto para o mesmo usuário.
Não deve ser possivel cadastrar um novo aluguel caso já exista um aberto para o mesmo carro.