# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


# Conteúdo Técnico

## **Javascript, básicos de sintaxe**

### **Variáveis:**
> 1. **Var:** Pode ser redeclarada e alterada, independente do bloco de códigos, modo mais antigo de declarar;
> 2. **Let:** Pode ter seu valor alterado contanto que esteja no mesmo bloco de códigos;
> 3. **Const:** Cria uma constante com valor fixo, não podendo se alterar.

Ex: ```var abc = 'xyz'```
    ```console.log(abc)```

Podemos somar as variáveis e realizar cálculos com o computador, dessa forma:

Ex: 
```const a = 66```; 
```const b = 23```;
```const subtracao = (a - b)```

### **String:**
> Strings guardam informações em formas de texto, e há comandos para checar uma posição em uma lista (```indexOf```), e tamanho (```.length```), que são frquentemente usados.
> Existe, também, a opção de **concatenar** strings, somando elas umas as outras para formar uma frase, e também separar os elementos de uma string

Ex: ```console.log('Oi' + ' ' + 'ser' + ' ' + 'humano')```;
    ```stringEx = "Vermelho Laranja Amarelo Verde Azul Roxo"
       resultado = stringEx.split("");
       console.log (resultado)```

### **Tipos primitivos de dados:**

> 1. **BOOLEAN:** true/false;
> 2. **Number:** valores numéricos, podendo ser inteiro ou decimal;
> 3. **NULL:** valor vazio;
> 4. **Undefined:** valor não definido.

### **If/else:**
> É uma função que serve para responder de acordo com um parâmetro, por exemplo, se o resultado for maior ou igual a 3, o console vai responder "correto", se for menor do que 3, o console pode dizer "incorreto" e assim por diante.
>
Sintaxe: ```if (exemplo1 > exemplo2) {
  console.log(soma(exemplo1, exemplo2))
} else if (exemplo1 < exemplo2) {
  console.log(subtrair(exemplo1, exemplo2))
} else {
  console.log("blank")
}
### **Array e Concatenar:**
O Array é uma forma de criar uma lista de elementos usando uma variável específica. Dentro dessa lista, é possível saber a **localização** de um certo elemento, **concatenar** duas listas diferentes, **remover** um elemento solicitado, colocar em **ordem alfabética** e **contar o total de elementos** incluidos na lista, **divide** a lista, **concatena** as listas, dessa forma (respectivamente):

Ex: ```const Saboresjujuba = ["morango", "laranja", "limão", "uva", "abacaxi"];```

> 1. **Consulta por index e mostra o nome do elemento:** ```console.log(Saboresjujuba[0])```
> 2. **Consulta por nome e mostra o index:** ```const localizacao = Saboresjujuba.indexOf("laranja");        console.log(localizacao)```
> 3. **Remove o último elemento e mostra o elemento removido:** ```console.log(Saboresjujuba.pop());```
> 5. **Adiciona elementos no final e mostra a quantidade de elementos:** ```console.log(Saboresjujuba.push("amora"));```
> 6. **Coloca em ordem alfabética:** ```console.log(Saboresjujuba.sort());```
> 7. **Conta os elementos:** ```console.log(Saboresjujuba.length);```
> 8. **Divide o Array em 2:** Utilizando primeiro o contador de elementos (.length);  ```const sacoJujuba1 = Saboresjujuba.slice(0, tamanhoJujubas /2);         constsacoJujuba2 =  Saboresjujuba.slice(tamanhoJujubas/2);```
> 9. **Concatenando Arrays:** ```const juntarSacosjujuba = sacoJujuba1.concat(sacoJujuba2);      console.log(juntarSacosjujuba)```
> 10. **Reverter a ordem do Array:** ```Saboresjujuba.reverse();```

### **Function:**
> O Function serve como um substituto para códigos específicos, como por exemplo uma soma, só que com o benefício que não é necessário criar sempre uma nova variável ou reescrever o código inteiro, poupando bastante tempo de um programador.

Sua sintaxe funciona assim, por ex:  ```function nome (parâmetro) {
                                      return parâmetro```

### **Prompt e Alert:**
> Ambos funcionam de uma maneira parecida, porém, o prompt permite que você possa digitar uma resposta ao que o código diz, enquanto o alert é um simples pop-up que serve, como o próprio nome sugere, alertar ou comunicar algo sem ser no console.log, sem precisar clicar > em run.

Sintaxe: ```const nome = prompt("pergunta")```;
         ```alert = ("aviso")```
         
### **Switch Case:**
> O switch case trabalha em conjunto com o prompt para poder dar respostas específicas para nomes específicos que estejam incluídos em sua lista, para assim dar respostas coerentes (inclusive, mesmo se o nome não estiver incluso, o código acaba com 'default', que é utilizado para responder a nomes que não tenham uma resposta já inclusa no código)

Sintaxe: ```switch (feriadosnac) {
            case "janeiro":
            console.log("1 mês do calendário gregoriano")
            break;
            case "dezembro":
             console.log ("12 mês do calendário gregoriano")
            break;
            default: 
            console.log ("esse mês não existe")
            }```

### **Operadores:**

**Comparativos:**
> 1. ```==``` , igual;
> 2. ```===``` , igual;
> 3. ```>``` , maior que;
> 4. ```<```'' , menor que;
> 5. ```>=``` , menor igual a;
> 6. ```<=``` , maior igual a;
> 7. ```!==``` , diferente;
> 8. ```!=``` , diferente.


**Matemáticos**
> 1. ```+``` , mais;
> 2. ```-``` , menos;
> 3. ```*``` , multiplicar;
> 4. ```/``` , divisão;
> 5. ```%``` , módulo;
> 6. ```**``` , potência.



## Atividades desenvolvidas

[Aula 1](https://codepen.io/ed-the-scripter/pen/NWZgvJZ?editors=0012),
[Aula 2](https://codepen.io/ed-the-scripter/pen/PorENGO),
[Aula 3](https://codepen.io/ed-the-scripter/pen/yLdQEQy),
[Aula 4](https://codepen.io/ed-the-scripter/pen/zYVbOwX),
[Aula 4](https://codepen.io/ed-the-scripter/pen/zYVbOwX),
[PWMF - Jogo](https://codepen.io/ed-the-scripter/pen/ExqYYvm),
[Aula 5](https://codepen.io/ed-the-scripter/pen/PoMGOwq),
[Aula 6](https://codepen.io/ed-the-scripter/pen/NWQbybm)
