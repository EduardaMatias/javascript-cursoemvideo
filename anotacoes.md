# JavaScript - Curso em vídeo.

alert() -> exibe um alerta na tela;
confirm() -> parecido com o alert mas com a opção de confirmar ou cancelar;
prompt() -> forma de interagir com o usuário.

---

var a1 = carro2 -> a1 recebe carro2.

---

identificadores:

podem começar com letra, $ ou _;
não podem começar com números;
é possíel usar letras ou números;
é possível usar acentos e símbolos;
não podem conter espaços;
não poder ser palavras reservadas.

---

alguns tipos primitivos:

number;
string;
boolean.

---

coisas importantes:

(number +  number) adição
(string + string) concatenação

o prompt trata todos os valores como string 

Number.parseInt(n) -> transforma em numero inteiro;
Number.parseFloat(n) -> transforma em numero inteiro;
Number(n) -> transforma em numero.

para convertar de numero para string:

string(n)
n.toString()

--- 

formatando strings

`eu estou aprendendo ${s}`
`${nome} tirou ${nota} na prova`

s.length -> tamanho da string
s.toUpperCase() -> transforma tudo em maiúsculas
s.toLowerCase() -> transforma tudo em minusculas

---

formatando numeros 

n.toFixed(2);
n.toFixed(2).replace('.', ',') -> trocar de ponto para virgula
n.toLocaleString('pt-BR', {style: 'currency', currency: 'BRL'}) -> convertendo para real

--- 

operadores

aritméticos (+, -, *, /, %, **)

atribuição (= -> recebe)

autoatribuição
var n = 3 
n = n + 4 (n += 4)
n = n - 5 (n -= 5)
n = n * 4 (n *= 4)
n = n /2  (n /= 2)
n = n ** 2 (n **= 2)
n = n % 5 (n %= 5)

incremento/decremento
x++
x--

relacionais (>, >=, <, <=, ==,===(identico), !=, !==)

lógicos (!, &&, ||)

ternário (?, :)
teste ? true : false
media >= 7 ? "Aprovado" : "Reprovado"
se a media for maior do que 7 o aluno será aprovado, se não o aluno será reprovado
