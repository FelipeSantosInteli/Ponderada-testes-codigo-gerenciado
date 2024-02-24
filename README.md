# Relatório sobre Testes Unitários em C# usando Visual Studio

https://learn.microsoft.com/pt-br/visualstudio/test/walkthrough-creating-and-running-unit-tests-for-managed-code?view=vs-2022

O tutorial explorado neste relatório utiliza o Visual Studio 2022 como ambiente de desenvolvimento e a linguagem de programação C# para escrever os testes unitários. Este documento oferece um resumo dos conceitos aprendidos durante a exploração desses testes. Os testes unitários são uma prática essencial no desenvolvimento de software para verificar o comportamento de partes individuais do código, permitindo detectar e corrigir erros de forma eficiente e garantir a integridade do código ao longo do tempo

## Conceitos Aprendidos
Durante a exploração do tutorial, foram abordados e aprendidos os conceitos à seguir:

1. **Escrita de Testes Unitários**: Foram abordadas técnicas para escrever testes unitários, incluindo a definição de casos de teste, a utilização de assertivas para verificar o comportamento esperado e a organização dos testes em métodos separados.

2. **Execução de Testes**: O tutorial demonstrou como executar os testes unitários dentro do Visual Studio, tanto de forma individual quanto em conjunto, para verificar se o código está funcionando conforme o esperado.

4. **Análise de Resultados**: Foi discutido como interpretar os resultados dos testes unitários, identificando quais testes passaram e quais falharam, facilitando a localização e correção de possíveis problemas no código.

<img alt="primeira execução" src="./assets/Captura de tela 1.png">

Aqui é possível verificar se o saldo final está conforme o esperado por meio do método Assert.AreEqual. Para isso, é definido um novo objeto BankAccount com um saldo inicial e, em seguida, retira um valor válido. Métodos como Assert.AreEqual, Assert.IsTrue e outros são frequentemente usados em testes de unidade.

Após corrigir o código do BankAccounts de **_m_balance += amount_** para **_m_balance -= amount_** o test executa sem erro

<img alt="primeira execução" src="./assets/Captura de tela 2.png">

Além disso, seguindo o tutorial, foram abordados outros tipos de testes

<img alt="primeira execução" src="./assets/Captura de tela 3.png">
<img alt="primeira execução" src="./assets/Captura de tela 4.png">
<img alt="primeira execução" src="./assets/Captura de tela 5.png">
