#ANOTAÇOES;
 background-color: == COR DE FUNDO
 text-align: == ALINHAMENTO



# HTML
  HyperText Markup Language

    -Hiper Texto?
    -Marcação
      -tags
      -atributos
    -Linguagem
      -Maneira de escrever



# CSS
  # DECLARAÇÃO
    - Seletor 
    - Propriedade e Valor

  # CONCEITOS 
    - Cascata
    - Especificidade
    - Box Model

#JavaScript

    1. Variaveis
    let estaChovendo = true
    const meuNome = "Mayk"

    2. Tipos de Dados 
    String
    ""
    ''

    Number
    12 - Integer (+ -)
    3.2 - Float (+ -)

    Boolean
    true false
    const maiorDeDezoito = false

    undefined - indefinido

    3. Operadores 
    Atribuição (ex: =)
    atribui Valor
    let n1 = 12
    let n2 = 3

    console.log(n1 + n2)

    Aritmeticos (ex: * / + -)
    calculos matematicos simples 

    Concaternação de String (+)

    Comparação (ex: > < == )
    trasforme a expressão em true ou false
    const maiorQue = 1 > 2 false
    const igual = 1 == 1 true

    4. Condicional (if/else)
    const idade = 17
    const maiorDeDezoito = idade >= 18 

    if(maiorDeDezoito) {
      alert("Pode tirar carteira de motorista")
      }
      else {
        alert("Não pode tirar")
    }

    5. Estruturas de dados 
    Array - Vetor - Lista
    Array ------ 0  1 2 3
    const temperaturas = [23,3,32.2,1,5]

    Object
    const pessoa = {
      nome: "Mayk",
      idade:38,
      filhos: ["K", "E", "j", "L", "G"]
    }

    console.log(pessoa.filhos[3])

    6. Function
    1. Criação
    function nomeDaFunção() {
      console.log('codigo dentro da dunção')
    }

    2.Execução
    nomeDaFunção()

    Parametros
    function sopa(a, b) {
      console.log(a + b)
   
      soma(34, 45)
      soma(98, 54)

      Retorno
      function soma(a, b) {
        return a + b
      }

      console.log(soma(2, 2))

      7. Extensões da linguagem (ex: math, Date ...)

      Math.random()
      Math.floor(1.2)
      Math.ceil(1,2)
      Math.Pi 

      8. DOM - Document object Model

      window
      window.alert("alerta")
      document 
      document.write("texto")
      manipular elementos
      document.documentElement.style.background = "black"