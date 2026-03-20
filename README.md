# 📋 Gerenciador de Itens em JavaScript

Este projeto é um sistema simples e interativo desenvolvido em JavaScript que permite ao usuário gerenciar uma lista de itens diretamente no navegador utilizando `prompt` e `alert`.

---

## 🚀 Funcionalidades

O programa oferece um menu com as seguintes opções:

1. Adicionar um item  
2. Exibir todos os itens  
3. Atualizar um item existente  
4. Remover um item  
5. Sair do programa  

---

## 🛠️ Como funciona

- O sistema utiliza um **array (`arranjo`)** para armazenar os itens.
- A interação com o usuário é feita através de:
  - `prompt()` → entrada de dados  
  - `alert()` → saída de informações  
- Um loop `do...while` mantém o programa em execução até que o usuário escolha sair.

---

## 📌 Estrutura do Código

### 🔹 `menu()`
Exibe o menu principal e retorna a opção escolhida pelo usuário.

### 🔹 `adicionarItem(arranjo)`
Adiciona um novo item ao array, validando se a entrada não está vazia.

### 🔹 `exibirItem(arranjo)`
Exibe todos os itens armazenados, mostrando seus índices.

### 🔹 `atualizarItem(arranjo)`
Permite atualizar um item existente com base no índice informado pelo usuário.

### 🔹 `removerItem(arranjo)`
Remove um item do array utilizando o método `splice()`.

---

## ⚠️ Validações Implementadas

O sistema trata diversos possíveis erros de entrada:

- Cancelamento do `prompt` (`null`)
- Entrada de valores não numéricos (`NaN`)
- Índices inválidos (menores que 1 ou maiores que o tamanho do array)
- Strings vazias ou compostas apenas por espaços

---

## ▶️ Como executar

1. Copie o código JavaScript
2. Cole dentro de um arquivo HTML, por exemplo:

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Gerenciador de Itens</title>
</head>
<body>

<script>
    // Cole aqui o código JavaScript
</script>

</body>
</html>
```
##Link Vercel
** [clique aqui](https://crudpuro-k5s1vxkms-nayv380s-projects.vercel.app/)
