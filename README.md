# Conceitos-JS
Repositório criado com intuito de colocar conceitos que aprendi trabalhando com Angular, React e afins.

## JSX
JSX é uma extensão de sintaxe para JavaScript. É semelhante a uma linguagem de template, mas com todo o poder do JavaScript. JSX é compilado para chamadas React.
Com ele é possível colocar HTML no Javascript

## Arrow Function
Uma forma de criar funções com uma estrutura mais curta no JS, permitindo ter um retorno implícito, que são valores retornados sem ter que usar a palavar return. 
Com Arrow Function, não é preciso declarar uma função como ```function```

#### Sem Arrow Function
```
const sayHello = function(name) {
    return `Seja bem-vindo ${name}!!!`;
};
```
#### Com Arrow Function
```
const sayHello = name =>{ 
   `Seja bem-vindo ${name}!!!`
};
```
## Props

Props, que é uma abreviação de properties, ou propriedades, são informações que podem ser passadas para um componente. Pode ser uma string, um número, até mesmo uma função
``` 
function Welcome(props) {
  return <h1>Hello, {props.name}</h1>;
}
```
## State
State deve servir para guardar valores/estados da aplicação que mudam com o uso da mesma, para guardar uma alteração de estado que pode ter efeito na renderização do próprio componente
```
 this.state = {
      isVisorActive: false
    }
```
