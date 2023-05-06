## Desafio DIO.

##### Este código realiza o calculo da media de 6 números positivos, ignorando os valores negativos.

Método: Criação de um Scanner denominado leitor, permitindo a entrada dos dados. 

Temos as seguintes variáveis:

int cont = 0;

double media = 0;

double valor = 0;

double num = 0;

Um laço de repetição "for" vai limitar a entrada de valores em seis e estes valores vão ser atribuídos a variável num. Dentro do "for" possui uma estrutura condicional "if", que apenas aceita num maior que zero, e a variável valor vai receber a soma de todos estes valores. A cada valor aceito a variável cont vai sofrer adição de um.

Fora do "for" a variável media vai ser a variável valor dividida pela variável num. Em seguida e impresso o valor da variável de cont, informando o numero de valores positivos, em seguida vai ser impresso a variável media utilizando String.format("%.1f") para limitar o valor da media a 1 casa decimal.



