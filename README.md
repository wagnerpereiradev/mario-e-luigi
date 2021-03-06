# Mario & Luigi
### Solução para um problema

Uma seguradora para carros Mario & Luigi está trabalhando com alta demanda de serviços e precisa se modernizar para poder crescer com qualidade. A empresa não possui um banco de dados completo e faz diversas anotações em papel ou em Excel o que prejudica muito o gerenciamento das equipes, das receitas e dos recursos.

Como contratado eu ofereci a eles uma solução digital de um banco e o primeiro passo para isso é o planejamento desses dados: O que eles devem fazer? Como devem fazer? Quais são as principais informações?

Elaborei um diagrama para uma seguradora de automóveis com as seguintes entidades: Cliente, Apólice, Carro e Acidentes.

## Diagrama

![Diagrama](./Mario&Luigi.png)

### Cliente:
* Renavam (Identificador)
* Nome Completo
* Data de Nascimento
* Endereço
* Telefone
* Celular

**Cliente** pode ter uma **Apólice**

### Apólice
* ID - Numérico (Identificador)
* Valor

**Apólice** cobre um ou mais **Carros**

### Carro
* Chassi
* Placa
* Marca
* Modelo
* Ano
* Proprietário

**Carro** pode ter um ou mais **Acidentes**

### Acidentes
* ID do fato (Identificador)
* Data do fato
* Local do fato
* Hora do fato
* Envolvidos
  * Cliente
  * Outros

Diagrama disponível para download neste repositório, em formato brModelo **.brM3**.

*Wagner R. Pereira 2022*
