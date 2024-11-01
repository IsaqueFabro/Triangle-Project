# Triangle Area
### Calculadora de Área de Triângulo

Este é um projeto acadêmico em Java que calcula a área de um triângulo com base nos valores de base e altura fornecidos pelo usuário. O programa inclui duas classes: Triangulo, que modela as propriedades e o cálculo do triângulo, e Main, que gerencia a entrada de dados do usuário e exibe o resultado da área.

### Estrutura do Projeto

model/Triangle.java: Contém a classe Triangle, que possui campos para a base e a altura, além de métodos para definir e obter esses valores. Também inclui um método para calcular a área.

main/Main.java: Contém o método principal, que cria um objeto Triangle, solicita ao usuário que insira a base e a altura, e depois exibe a área calculada.

### Como Executar

Compile Triangle.java e Main.java.

Execute Main, que solicitará ao usuário que insira a base e a altura do triângulo.

O programa exibirá a área calculada.

### Principais Desafios

Um dos principais desafios deste projeto foi lidar com a entrada de dados do usuário e garantir que o cálculo da área seja preciso para valores decimais. Usar Scanner.nextDouble() para a entrada permite que o programa aceite números com ponto flutuante, tornando os cálculos mais precisos.
