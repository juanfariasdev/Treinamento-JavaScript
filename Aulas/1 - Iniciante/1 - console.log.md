## Console.log
O console.log serve para exibir uma mensagem para o usuário via o console.

Ele recebe argumentos, podendo ser vários separados por vírgula
O Argumento serve para falar o que ele deve exibir.

console.log(argumento1, argumento2, argumento3)

### Texto
Caso queira colocar um texto para ser exibido, pode ser declarado dentro do próprio console.log, ou fora como uma "Variável"

Dentro do próprio console deve ser envolvido usando Aspas (""), ('') ou (``):
```shell
console.log("Bem Vindo ao treinamento");
```
Caso esqueça as Aspas, ele irá procurar uma variável com o nome que colocou, assim irá apresentar um erro.

Fora  do próprio console:
```shell
var texto = "Me segue no instagram: juanfarias.dev"
console.log(texto);
```

É muito importante saber as diferenças das Aspas.

Aspas duplas("") e aspas simples ('') são muito parecidas, porém as Aspas duplas("") permite colocar Aspas simples('') no texto:
```shell
console.log("Já seguiu meu perfil no 'Github'?");
```

Ou vice-versa: 
```shell
console.log('Estou falando muito "sério"!!');
```

A Craze serve deixa usar Aspas duplas("") e aspas simples ('') e pode usar variáveis dentro do texto. da seguinte forma
```shell
let site = "https://juanpablofarias.com"
console.log(`Já 'olhou' meu "site?" ${site}`);
```
Não se preocupe com o "let" nesse momento, apenas saiba que ele serve para declarar uma variável e logo terá uma aula sobre os tipos de variável!

### Número
No caso do Número, não é necessário envolver com as Aspas 

```shell
console.log(123456, 12.332, 'Juan Pablo Farias');
```

### EXERCÍCIO
NÃO VALE COPIAR!!!
A Idéia é você aprender a fazer e não aprender a copiar!!!
 [Exercicio console.log](./exercicio/1%20-%20console.log.js).

Resolução: 
 [Exercicio console.log](./exercicio/resolucao/1%20-%20console.log.js).