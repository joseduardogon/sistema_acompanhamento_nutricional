**As 4 Classes Conceituais**

Classe 1: Paciente

Descrição: Representa a pessoa que receberá o atendimento e a prescrição.

Atributos (Privados -):

- nome: String

- cpf: String

- idade: int

- sexo: char

Métodos (Públicos +):

+ cadastrar()

+ alterar()

+ consultar()

Classe 2: AvaliacaoFisica

Descrição: Armazena os dados biométricos de um momento específico do paciente para realizar os cálculos exigidos no Escopo.

Atributos (Privados -):

- dataAvaliacao: Date

- peso: double

- altura: double

- nivelAtividade: double (Fator usado no cálculo)

- vet: double (Valor Energético Total)

- net: double (Necessidade Energética Total)

Métodos (Públicos +):

+ calcularVET(): double

+ calcularNET(): double

Classe 3: Alimento

Descrição: Representa um item do "Banco de Alimentos", contendo a tabela nutricional base.

Atributos (Privados -):

- nome: String

- porcaoBaseGramas: double

- calorias: double

- carboidratos: double

- proteinas: double

- lipidios: double

Métodos (Públicos +):

+ cadastrar()

+ obterInformacaoNutricional(): String

Classe 4: PlanoAlimentar

Descrição: A dieta montada em si, que agrupará os alimentos e validará se bate com as necessidades calculadas na avaliação.

Atributos (Privados -):

- titulo: String

- dataCriacao: Date

- totalCalorias: double

Métodos (Públicos +):

+ adicionarAlimento(alimento: Alimento)

+ removerAlimento(alimento: Alimento)

+ validarPlano(netEsperada: double): boolean