# HTML
- HyperText Markup Language

- Hiper Texto?
- Marcação
 - tags
 - atributos
- Linguagem
 - maneira de escrever

# CSS

- Apresentação visual para o cliente
- Estilos para o HTML
- Cascading Style Sheets
 - Folha de Estilo em Cascata

# Declaração
- Seletor
- Propriedade e Valor

# Conceitos
- Cascata
- Escecificidade
- Box Model
- Display block vs inline

# JavaScript

1. Variáveis
* let estaChovendo = true
* const meuNome = "Ylan"
* estaChovendo = false -> pode ser alterado
* meuNome = "Brito" -> nao pode ser alterado
#
2. Tipos de Dados
* String -> cadeia de caracteres
* " "
* ' '
#
3. Number
* 12 - Integer (+ -)
* 3.2 - Float (+ -)
#
4. Boolean
* true ou false
* const maiorDeDezoito = false
#
4. Undefined
* indefinido
#
5. Operadores
* Atribuição (ex: =)
* atribui valor
* let n1 = 12
* let n2 = 3
#
6. Aritméticos (ex: * / + - )
* calculos matemáticos simples
* consoe.log(23 + 4)
# 
7. Concatenação de String (+)
* console.log("23" + 4 + "abc")
#
8. Comparação (ex: > < == )
* transforma a expressão em true ou false
* const maiorQue = 1 > 2 // false
* const igualA = 1 == 1 // true
#
9. Condicional (if/else)
* const idade = 17
* const maiorDeDezoito = idade >= 18
* if(maiorDeDezoito) {
*    alert("Pode tirar carteira de motorista")
* } else {
*    alert("Não pode tirar")
* }
# 
10. Estrutura de dados
* Array - Vetor - Lista
* Array ----- Indices ->  0     1   2  3
* const temperaturas = [23.3, 32.2, 1, 5]
* console.log(temperaturas[1])
#
11. Object
* const pessoa = {
*    nome: "Ylan",
*    idade: 38,
*    filhos: ["K", "E", "J", "L", "G"]
* }
* console.log(pessoa.filhos[2])
#
12. Function
* 1. Criação
* Function nomeDaFuncao() {
*    console.log('código dentro da função')
* }
*
* 2. Execução
* NomeDaFuncao ()
*
* Parâmetros
* function soma(a, b) {
*    console.log(a + b)
* }
* soma(34, 45)
* soma(90, 54)
*
* Retorno
* function soma(a, b) {
*    return a + b -> tirar valores de dentro da função
* }
* const multiplicada = soma(2, 2) * 4
* console.log(multiplica)
* console.log(soma(2, 2))
#
7. Extensões da linguagem (ex.: Math, Date ...)
* Math.random() -> número randomico entre 0 e 1
* Math.floor(1.2) -> arrendoda para baixo
* Math.ceil(1.2) -> arrendoda para cima
* Math.PI -> número do PI
#
8. DOM - Document Object Model
* window
* window.alert("alerta")
* document
* document.write("texto")
* manipular elementos
* document.documentElement.style.background = "black"