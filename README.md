# Calculator-Rest-ASP.NET

Este projeto consiste em uma calculadora RESTful simples usando ASP.NET. Ele fornece endpoints para realizar operações matemáticas básicas (soma, multiplicação, divisão, média e raiz quadrada) com números fornecidos via parâmetros de URL.

## Funcionalidades

### **Sum**
- **Endpoint:** `/calculator/sum`
- **Descrição:** Realiza a soma entre dois números.
- **Parâmetros:** `firstNumber` e `secondNumber`
- **Método HTTP:** GET
- **Exemplo de uso:** `/calculator/sum?firstNumber=2&secondNumber=3`

### **Multiplication**
- **Endpoint:** `/calculator/multiplication`
- **Descrição:** Realiza a multiplicação entre dois números.
- **Parâmetros:** `firstNumber` e `secondNumber`
- **Método HTTP:** GET
- **Exemplo de uso:** `/calculator/multiplication?firstNumber=2&secondNumber=3`

### **Division**
- **Endpoint:** `/calculator/division`
- **Descrição:** Realiza a divisão entre dois números.
- **Parâmetros:** `firstNumber` e `secondNumber`
- **Método HTTP:** GET
- **Exemplo de uso:** `/calculator/division?firstNumber=6&secondNumber=2`

### **Media**
- **Endpoint:** `/calculator/media`
- **Descrição:** Calcula a média entre dois números.
- **Parâmetros:** `firstNumber` e `secondNumber`
- **Método HTTP:** GET
- **Exemplo de uso:** `/calculator/media?firstNumber=4&secondNumber=6`

### **Raiz Quadrada**
- **Endpoint:** `/calculator/raizquadrada`
- **Descrição:** Calcula a raiz quadrada de um número.
- **Parâmetro:** `number`
- **Método HTTP:** GET
- **Exemplo de uso:** `/calculator/raizquadrada?number=9`

## Instruções de Uso

1. Clone este repositório: `git clone <URL-do-repositório>`
2. Abra o projeto em sua IDE preferida (Visual Studio, por exemplo).
3. Execute o projeto.
4. Acesse os diferentes endpoints utilizando um cliente HTTP (como Postman ou seu navegador web).

## Observações

Certifique-se de passar os parâmetros corretos para cada endpoint. Os endpoints retornarão resultados ou mensagens de erro conforme a entrada fornecida.
