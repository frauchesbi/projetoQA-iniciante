# logica-de-programacao-algoritimo

Este repositório contém exercícios, anotações e evidências, com foco em raciocínio lógico, algoritmos, pseudocódigo e fundamentos de programação.

## Meus estudos:
- O que é programação, conhecer suas principais áreas de atuação e entender o mercado.
. Quando falamos em lógica de programação, estamos nos referindo à capacidade de organizar e estruturar ideias para resolver problemas por meio do código. Antes mesmo de escrever uma linha de programação, precisamos pensar como um programa pensa: em etapas bem definidas, instruções claras e decisões baseadas em condições.

## Evidências de Aprendizado:

.Comecei baixando o Visual Studio Code preparando o ambiente do meu projeto.
.Baixei o projeto base que usei durante o curso. 

-Esse projeto vem com tudo o que eu precisei para acompanhar as aulas deste curso.
Ele contém:
{Um arquivo HTML, responsável por estruturar o site e conectar os outros arquivos;
Um arquivo CSS, que define o estilo visual da página (cores, fontes, tamanhos, etc.);
Um arquivo JavaScript, onde escrevi os códigos e exercícios.}
Embora o projeto traga vários arquivos, neste momento foquei apenas no arquivo JavaScript, pois é nele que colocarei em prática tudo o que está aprendendo sobre lógica de programação.
-O arquivo que utilizei para meu aprendizado: https://github.com/alura-cursos/logica-js/archive/refs/heads/projeto_inicial.zip

Aula 1:
-Iniciando com JavaScript: Carregando o projeto base
O foco da aula foi entender o jogo do número secreto, onde um número é escolhido e o jogador tenta adivinhá-lo. Aprendi a usar o comando `alert` em JavaScript para exibir mensagens ao usuário. A primeira mensagem exibida foi "Olá, Mundo", que foi posteriormente alterada para "Boas-vindas ao jogo do Número Secreto". Também enfatizamos a importância de usar ponto e vírgula no final das instruções e a necessidade de salvar as alterações no código.
Aprendi a criar variáveis em JavaScript utilizando a palavra-chave let, armazenando valores como o numeroSecreto. Utilizei os comandos alert para exibir mensagens e prompt para solicitar que o usuário insira um número. Compreendi a importância de nomear variáveis de forma clara e a necessidade de testar o código para identificar e corrigir erros. Introdução à comparação de variáveis em JavaScript. Uso do comando if para verificar condições. Importância dos parênteses na estrutura do if. Diferença entre atribuição (=) e comparação (==). Criação de variáveis para armazenar valores do prompt. Estrutura do código para comparar o valor do chute com o numeroSecreto. Uso de console.log() para exibir mensagens no console do navegador. Demonstração de como visualizar mensagens no console usando a ferramenta de inspeção do navegador.

Aula 2: 
Condicionais e Comentários em JavaScript
Comentários em JavaScript:
Utilização do símbolo // para criar comentários que não são interpretados como código.
Estruturas Condicionais:
.if: Usado para verificar condições (ex: se o chute é igual ao número secreto).
.else: Usado para definir ações quando a condição do if não é atendida.
Interação com o Usuário: Preferência por alert para feedback ao usuário em vez de console.log.
Uso de Variáveis: Ao usar console.log, não colocar aspas ao referenciar variáveis para exibir seus valores corretamente.



![Captura de tela 2025-07-02 184437](https://github.com/user-attachments/assets/6b249683-3539-425f-9f3b-c723d6f6bf4c)


Aula 3:
-Condicionais e Concatenação
Concatenação de strings em JavaScript com Template Strings.
.Mudança do Número Secreto: Alteração do número secreto de 5 para 4.
Problema: Necessidade de atualizar manualmente o número em várias partes do código.
Solução: Uso de variáveis para armazenar o número secreto, evitando alterações manuais.
Template Strings: Utilização de crases (`) para concatenar texto e variáveis.
Sintaxe: ${variavel}.
Resultado: Mensagens dinâmicas que refletem o número secreto atual.

![Captura de tela 2025-07-02 185835](https://github.com/user-attachments/assets/1aec5cb2-172e-4de6-a47a-b8cf7115fc19)



https://github.com/user-attachments/assets/89af35a9-955f-4612-9131-e334a2fddb49

Aula 4:
-Uso do Live Server no Visual Studio Code.
Objetivo: Atualizar automaticamente o navegador ao fazer alterações no código.
.Instalei o Live Server
-Aprendi: O uso manual do ponto e vírgula no JavaScript é recomendado para evitar erros e garantir a clareza do código, já que a inserção automática pode causar confusões.
-As principais mudanças nessa aula foram:
"Dicas ao Jogador": O jogo informa se o número secreto é maior ou menor que o palpite.
-Template Strings: Utilizei template strings para formatar as mensagens de forma dinâmica.
Estrutura de Condições: Implementei condições if e else para fornecer feedback imediato.
Essas melhorias tornaram o jogo mais interativo.

Aula 5:Loops e Tentativas com while
.Loop while: Executa instruções enquanto uma condição for verdadeira.
Aplicação no Jogo: Solicita chutes até que o chute seja igual ao número secreto.
Estrutura do Código: Inicializa chute como vazio.
Solicita chute e verifica se é igual, maior ou menor que o número secreto.
Legibilidade: Código deve ser bem estruturado e alinhado.
Operadores de Comparação: Utiliza !=, ==, e > para comparações.
Teste do Jogo: Funciona corretamente, exibindo mensagens apropriadas.


![Captura de tela 2025-07-02 194701](https://github.com/user-attachments/assets/5d2a8b78-3243-4544-a401-78b05a10ac51)


Aula 6: Aprendemos a contabilizar as tentativas no jogo do número secreto. Criamos a variável tentativas, que começa em 1, e incrementamos seu valor quando o jogador erra. Ao acertar, exibimos uma mensagem informando quantas tentativas foram feitas. Também vimos que podemos usar 'tentativas++' para simplificar o incremento.

ficando então assim: 
   na linha 5:                let tentativas = 1;
     na linha 12:             alert(`Isso ai! Você descobriu o número secreto ${numeroSecreto} com ${tentativas} tentativas`);
       na linha 20:           tentativas++;

Aula 7:
-Validação da Mensagem: Quando o usuário acerta o número na primeira tentativa, a mensagem exibida estava errada, pois usava "tentativas" no plural, mesmo que fosse apenas uma.
-Uso do break: Para interromper o laço de repetição (while) quando o número secreto é adivinhado, foi introduzido o comando break. No entanto, isso fez com que a mensagem de sucesso não fosse exibida.
-Reorganização do Código: A mensagem de sucesso foi movida para fora do laço while, garantindo que ela seja exibida após o jogo terminar.
-Concordância Gramatical: Foi criada uma condição para exibir "tentativa" no singular ou "tentativas" no plural, dependendo do número de tentativas feitas pelo usuário.
.Assim, o código foi ajustado para funcionar corretamente e exibir mensagens apropriadas ao usuário.
     foi adicionado o 'break;' na linha 12 

  ![Captura de tela 2025-07-02 202613](https://github.com/user-attachments/assets/7bf61699-652b-4aff-af9a-db171b82ef46)

removi a linha 13 para a linha 24 e modifiquei:

if (tentativas > 1) {
    alert(`Isso ai! Você descobriu o número secreto ${numeroSecreto} com ${tentativas} tentativas.`);
} else {
    alert(`Isso ai! Você descobriu o número secreto ${numeroSecreto} com ${tentativas} tentativa.`);
}

![Captura de tela 2025-07-02 202654](https://github.com/user-attachments/assets/5af51858-a0b0-4bd9-9aac-5119627dbe89)

Aula 8: 
Nesta aula, aprendi sobre o operador ternário em JavaScript, uma forma concisa de escrever condicionais if...else em uma única linha.
O que é: O operador ternário é uma alternativa para simplificar estruturas condicionais, especialmente quando se tem uma atribuição de valor baseada em uma condição.
Como usar: condicao ? valorSeVerdadeiro : valorSeFalso;
Exemplo prático:

let palavraTentativa = tentativas > 1 ? 'tentativas' : 'tentativa';
alert(`Isso ai! Você descobriu o número secreto ${numeroSecreto} com ${tentativas} ${palavraTentativa}.`);

Neste caso, a variável palavraTentativa recebe o valor "tentativas" se o número de tentativas for maior que 1, e "tentativa" caso contrário.
Benefícios:
Código mais limpo e legível.
Redução do número de linhas de código.

-Observações: Embora o operador ternário possa tornar o código mais conciso, é importante utilizá-lo com moderação para não comprometer a legibilidade, especialmente em condições complexas.

Aula 9: Nesta aula, aprendi como gerar números aleatórios em JavaScript utilizando a função Math.random().
Math.random(): Essa função retorna um número pseudoaleatório entre 0 (incluso) e 1 (excluso).
Multiplicando para aumentar o intervalo: Para obter números aleatórios em um intervalo maior, multiplicamos o resultado de Math.random() pelo valor máximo desejado. Por exemplo, Math.random() * 10 gera números entre 0 e 10 (excluindo o 10).
parseInt() para obter inteiros: Para remover as casas decimais e obter apenas a parte inteira do número, utilizamos a função parseInt(). Por exemplo, parseInt(Math.random() * 10) retorna um número inteiro entre 0 e 9.
Ajustando o intervalo: Para ajustar o intervalo para começar em 1 em vez de 0, podemos adicionar 1 ao resultado final. Por exemplo, parseInt(Math.random() * 10 + 1) retorna um número inteiro entre 1 e 10.

Em resumo, a combinação de Math.random(), multiplicação e parseInt() nos permite gerar números inteiros aleatórios dentro de um intervalo específico, o que é útil para criar jogos e outras aplicações que requerem aleatoriedade.

Aprendi a resolver um desafio prático no jogo do número secreto. O objetivo foi tornar o jogo mais flexível, permitindo que o jogador defina o valor máximo do intervalo de números.Para isso, criei uma variável chamada numeroMaximo para armazenar o valor máximo desejado. Em seguida, substituí o valor fixo 100 no código por essa variável, tanto no cálculo do número secreto quanto na mensagem exibida ao jogador. Para exibir o valor de numeroMaximo na mensagem, utilizei template strings, que me permitem inserir o valor de uma variável dentro de uma string de forma fácil e elegante. Com essas alterações, o jogo se tornou mais dinâmico e personalizável, permitindo que o jogador defina o nível de dificuldade. Além disso, revisei os conceitos de variáveis e template strings, e como utilizá-los em expressões matemáticas.
##
---
Meu projeto de "aprendendo o que é programação" ficou assim:

![Captura de tela 2025-07-03 175246](https://github.com/user-attachments/assets/71461ec2-b3a0-4170-b6d1-a8a1b9f1a5d9)

![Captura de tela 2025-07-03 175337](https://github.com/user-attachments/assets/132ec6bc-8feb-47e1-91d4-1c3d3000c9b7)

![Captura de tela 2025-07-03 175358](https://github.com/user-attachments/assets/b0792dd7-4dca-4306-a5d8-a444a0cd2872)

![Captura de tela 2025-07-03 175416](https://github.com/user-attachments/assets/da3b5599-2768-4314-89e4-9398b735f552)

![Captura de tela 2025-07-03 175748](https://github.com/user-attachments/assets/903f933a-2a10-4075-9a79-fd79ee8b4c97)

---
