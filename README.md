# Sintaxe Básica Javascript para Iniciantes

## Tipos de criações de variáveis:

- Boolean
```
var boolean = false;
```
- Number
```
var number = 1;
```
- Function
```
var example = function(){};
console.log(`A variável da ${example} tem o tipo ${typeof(funcao)}';
```

## Como declarar
- var -> variável global ou local, valor inicial nulo;
- let -> variável local de bloco, valor inicial nulo;
- const -> variável local de bloco, valor inicial obrigatório;

## Como realizar prints
- Console Log
```
console.log();
```
- Concatenação de Texto e Função -> `Texto ${variavel da função}`;
- Antes de usar uma variável em um programa JavaScript, você deve declará-la.

## String
Para incluir uma string literal em um programa JavaScript, basta colocar os caracteres da string dentro de um par combinado de aspas simples ou duplas.
```
var name = "javascript";
var name = 'javascript';
```
- para medir tamanho do texto, utilizamos a propriedade: ```name.length // 10 letras (javascript)```

## Condicional
### If e Else
```
if (n == 1) {
    // executa este bloco if
} else if () {
    // executa este bloco else if
} else {
    // executa este bloco else
}
```
[Saiba mais sobre Condicional IF e ELSE em JS](https://www.devmedia.com.br/javascript-if-else-criando-scripts-com-estruturas-condicionais/39686)

### Switch Case
```
switch (cargo) {
    case "gerente":
        salario *= 1.15;
        break;
    case "supervisor":
        salario *= 1.10;
        break;
    default:
        salario *= 1.05;
}
```
[Saiba mais sobre Condicional SWITCH CASE em JS](https://www.devmedia.com.br/javascript-switch/39761)

### Laço FOR
```
for (var i = 0; i < 5; i++) {
    // Will execute 5 times
}
```

## Arrays
- Em JavaScript, arrays são um tipo especial de objeto que representam um conjunto ordenado de valores numerados.
```
var a = ["dog", "cat", "hen"];
a.length // 3
```

## Objetos
- Um objeto em JavaScript é um conjunto não ordenado de valores nomeados.

Para criar um objeto vazio:
```
var obj = {};
```
Podemos criar um objeto com propriedades e métodos:
```
var obj = {
    name: "Carrot",
    "for": "Max",
    details: {
        color: "orange",
        size: 12
    }
}
```
E acessar as propriedades dessa forma:
```
obj.details.color      // orange
obj["details"]["size"] // 12
```

# Contribuição Open Source
### Instruções (PT/BR)
1. Faça um **Fork** deste repositório;
2. Clone localmente: `git clone https://github.com/SEUUSERNAME/JsSintaxe`;
3. Adicione o remote upstream para manter seu repositório local atualizado: `git remote add upstream https://github.com/adautodf/JsSintaxe`;
    > Utilize o comando `git pull upstream main` para baixar e mesclar as alterações no seu repositório local com base na branch `main` deste repositório original de onde você fez o fork, ou `git fetch upstream main` para baixar sem mesclar.
4. Crie uma nova **branch** e nomeie como `feat/community/seunomedeusuario`: `git checkout -b feat/community/seunomedeusuario`;
    > Exemplo: `git checkout -b feat/community/adautodf`
5. Crie um commit e adicione a mensagem indicando a adição do seu perfil `git commit -m"feat: add seunomedeusuario profile"`;
6. Envie as alterações para o seu repositório remoto `git push origin feat/community/seunomedeusuario`; 
7. Crie um **Pull Request**.

## Contribua
[![Star](https://img.shields.io/github/stars/adautodf/JsSintaxe?style=social)](https://github.com/adautodf/JsSintaxe/stargazers)
[![Forks](https://img.shields.io/github/forks/adautodf/JsSintaxe?style=social)](https://github.com/adautodf/JsSintaxe/forks)
[![GitHub Issues](https://img.shields.io/github/issues/adautodf/JsSintaxe?style=social)](https://github.com/adautodf/JsSintaxe/issues/)

 Este é um projeto feito para a comunidade, então sinta-se livre para contribuir sugerindo melhorias, adicionando códigos...
 Além disso, você também pode contribuir:
 
⚠️ Resolvendo, respondendo ou indicando **issues**

⭐ Adicionando aos favoritos (**star**) 

### Membros da comunidade que já contribuiram:
<a href="https://github.com/adautodf/JsSintaxe/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=adautodf/JsSintaxe"/>
</a>
