# estudando-js
Estudando javascript com Gusta Guanabara.



// **************************************************** concatenando Strings ***********************************************\\

       // let n1 = Number(window.prompt('Digite um Número:  '));
       // let n2 = Number(window.prompt('Digite outro número:  '));
       // let s = n1 + n2;
       //  window.alert(`A soma entre ${n1} e ${n2} é igual a ${s}`); // concatenando com template Strings.

       //  **************************************************** Formatando Strings *******************************************\\

        // let nome = window.prompt('Qual é seu nome ?');
        // document.write(`Olá, <strong>${nome}</strong>! Seu nome tem  ${nome.length} letras.<br>`); // .length Calcula quantos itens foram digitado
        // document.write(` Seu nome em Maiúsculas é ${nome.toUpperCase()}<br>`); // Muda toas as letras para MAIÚSCULA
        // document.write(` Seu nome em Minuscula é ${nome.toLowerCase()}`); // Muda todas as letras para minúcula

       // **************************************************** Formatando números *********************************************\\

       // let n1 = Number(window.prompt('Digite um Número:  '));
       // document.write(`O Número digitado é: ${n1}<br>`);
       // document.write(`O Número com ponto é: ${n1.toFixed(2)}<br>`); // Acrescenta duas casas depois da vírgula
       // document.write(`O Número com virgula é: ${n1.toFixed(2).replace('.',',')}<br>`); // Troca o ponto por vírgula  
       // document.write(`O Valor em Reais é: ${n1.toLocaleString('pt-BR', {style: 'currency', currency: 'BRL'}).replace('.',',')}<br>`); // Transforma o número digitado em valores Reais
       /   / document.write(`O Valor em Dolar é: ${n1.toLocaleString('pt-BR', {style: 'currency', currency: 'USD'})}<br>`);  // Transforma o número digitado em valores Dolar 
       // document.write(`O Valor em Dolar é: ${n1.toLocaleString('pt-BR', {style: 'currency', currency: 'EUR'})}<br>`);  // Transforma o número digitado em valores Euro
    
        //**************************************************** Entendendo Operadores *********************************************\\

        // Aritiméticos  --> +  Soma || - Subtração || * Multiplicação || /  Divisão Real || %  Resto da Div Inteira || **  Potência EX:.(5 ** 2 = 25)
        
        // Ordem de Precedência 
        
        // [()] --> Será executado primeiro tudo que estiver entre parentese
        
        // [**] --> sempre depois do que esta entre parentese, se tiver parentese na operação, caso contrario será a primeinra
        
        // [*, /, %] --> Têm a mesma ordem de precedência, será executado sempre oque vier primeiro, da esquerda para direita
        
        // [+, -] --> Têm a mesma ordem de precedência, será executado sempre oque vier primeiro, da esquerda para direita

        // [ >, <, >=, <=, ==, !=, === ] --> Têm a mesma ordem de precedência, será executado sempre oque vier primeiro, da esquerda para direita

        // ! Negação [Não]

        // && Conjunção [E]

        // || Dijunção [OU]

        // Teste [?] True [:] False

        
        // ************************************************************************************************************************\\

        //                          ** Atribuição Simples --> Estou usando [] para mostrar a ordem de precedência **
        
        // var a = 5 + 3 = 8 --> Variavel agora está valendo 8
        
        // var b = a % 5 = 3 --> A=(8) divisão inteira por 5 variavel b igual a 3
        
        // var c = 5 * [b ** 2] = 45 --> Seguindo a ordem de precedência, b=(3)potência 2 vezes 5 a variavel c igual a 45
        
        // var d = 10 - [a / 2] = 6 -->  Seguindo a ordem de precedência, a=(8)dividido por 2 igual a 4 - 10 a variável d igual a 6
        
        // var e = [6 * 2] / d = 2 -->  Seguindo a ordem de precedência, 6 vezes 2 igual 12, dividido por d=(2) a variavel e igual a 2
        
        // var f = [b % e] + [4 / e] = 3 --> Seguindo a ordem de precedência, temos na mesma linha dois operadoes com a mesma precedência vamos executar da esquerda para direita
        // b=(3) resto da div e=(2) igual a 1, 4 divido por e=(2) igual a 2, a soma dos dois resultados igual a 3

        // *****************************************************************************************************************************\\

        //                                          ** Alto Atribuição **

        // Atribuição Simples    ||     Modo Simplificado      || Incremento / Decremento

        // var n = 3            

        // n = n + 4  = 7        ||      n += 4 = 7               n += 1    ||   n ++
        
        // n = n - 5  = 2        ||      n -= 5 = 2               n -= 1    ||   n -- 
        
        // n = n * 4  = 8        ||      n *= 4  = 8
         
        // n = n / 2  = 4        ||      n /= 2 = 4
        
        // n = n ** 2 = 16       ||      n **= 2 = 16
        
        // n = n % 5  = 1        ||      n %= 5 = 1   


       //***************************************************Relacionais *********************************************************************\\
        
       // 5 > 2 --> true [ 5 é maior que 2 ? Verdadeiro] 
       
       // 7 < 4 --> false [ 7 é menor que 4 ? Falso]

       // 8 >= 8 --> true [ 8 é maior ou igual a 8 ? Verdadeiro, aqui ele testa a duas condições ]

       // 9 <= 7 --> false [ 8 é maior ou igual a 8 ? Falso, aqui ele testa a duas condições ]

       // 5 == 5 --> true [ 5 é igual a 5 ? Verdadeiro]

       // 4 != 4 --> false [4 é diferente de 4 ? Falso]
        
       // 5 == '5' --> true [ 5 é igual a 5 ? Verdadeiro, aqui ele está testando se o valor é igual ]

       // 5 === '5' --> false [ 5 é identico a 5 ? Verdadeiro, aqui ele está testando se é identico, valor e tipo ]
        
        
       //**************************************************** Lógicos ***********************************************************************\\
        
        // ! Negação  [não]

        // && Conjunção [E] --> As duas condições precisam ser atendias 

        // || Dijunção [OU] --> Se uma condição for atendida, já é o suficiente


        //*************************************************** Ternário ***********************************************************************\\ 

        // Teste [?] True [:] False

        // {media >= 7.0 [?] "Aprovado" [:] "Reprovado"}
