# Calculadora de IMC (Índice de Massa Corporal)

> Aplicação desenvolvida para praticar **Lógica Matemática**, **Condicionais Encadeadas** e manipulação do DOM.

Este projeto calcula o IMC do usuário com base no peso e altura fornecidos. Além de entregar o resultado numérico, o sistema classifica automaticamente a situação do paciente (Abaixo do peso, Peso normal, Sobrepeso, Obesidade I, II ou III) seguindo os padrões da OMS.

## Tecnologias Utilizadas

- **HTML5** (Estrutura e Inputs)
- **CSS3** (Estilização com feedback visual de áreas)
- **JavaScript** (Cálculo matemático e lógica de intervalos)

## Funcionalidades

- [x] **Cálculo Preciso:** Aplica a fórmula `Peso / (Altura * Altura)` para encontrar o índice.
- [x] **Formatação de Dados:** Uso de `.toFixed(2)` para limitar o resultado a duas casas decimais, melhorando a leitura.
- [x] **Validação de Entrada:** Impede o cálculo caso os campos sejam zero, negativos ou inválidos.
- [x] **Classificação Detalhada:** Estrutura de `if/else if` complexa para cobrir todas as 6 faixas de classificação de peso.
- [x] **Feedback Visual:** Exibe o resultado e a classificação na tela sem recarregar a página.

## Aprendizados e Destaques do Código

1. **Lógica de Intervalos:** O maior desafio foi montar a estrutura condicional para verificar faixas de valores (ex: `soma >= 18.5 && soma <= 24.9`). Isso garante que o usuário caia exatamente na categoria correta.
2. **Matemática no JS:** Consolidação do uso de operadores aritméticos e precedência (parênteses) para a fórmula do IMC.
3. **Validação de Segurança:** Implementação de checks para garantir que a altura e peso sejam números positivos válidos antes de processar a conta.

## Como rodar o projeto

1. Clone este repositório.
2. Abra o arquivo `index.html` no navegador.
3. Insira seu peso (em Kg) e altura (em metros, ex: 1.75) e clique em "Calcular".

---
Desenvolvido por **Fabio** durante estudos de Lógica de Programação.
