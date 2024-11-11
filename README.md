# README

## Descrição

Este programa implementa uma série de exercícios em Java, utilizando a estrutura `switch-case` para realizar diferentes operações baseadas na escolha do usuário. O código permite a navegação entre 15 exercícios, oferecendo cálculos e verificações em diversos cenários, como operações com números, figuras geométricas e loops.

## Funcionalidades

- **Exercício 1**: Exibe o nome de um planeta.
- **Exercícios 2 e 3**: Solicita nome e idade do usuário e exibe essas informações.
- **Exercício 4**: Realiza cálculos de área para diferentes formas geométricas (retângulo, quadrado, losango, trapézio, paralelogramo, triângulo e círculo).
- **Exercício 5**: Verifica se três números são negativos, positivos ou neutros.
- **Exercício 6**: Identifica o maior número entre três valores distintos fornecidos pelo usuário.
- **Exercício 7**: Soma os dois maiores valores entre três números fornecidos.
- **Exercício 8**: Realiza a divisão entre dois números, com verificação do denominador.
- **Exercício 9**: Calcula a média aritmética de dez números fornecidos pelo usuário.
- **Exercício 10**: Verifica se quatro notas de um aluno são válidas (entre 0 e 10) e calcula a média para determinar se o aluno foi aprovado ou reprovado.
- **Exercício 11**: Imita uma contagem regressiva, representando uma bomba prestes a explodir.
- **Exercício 12**: Imprime números de 10 a 1 em sequência decrescente.
- **Exercício 13**: Solicita dois números inteiros e garante que o segundo número seja maior que o primeiro.

## Como Usar

1. **Pré-requisitos**:
    - JDK (Java Development Kit) 8 ou superior instalado.
    - IDE de desenvolvimento como IntelliJ, Eclipse ou VSCode com suporte a Java.

2. **Compilação e Execução**:
    - Compile o código com o comando: `javac Main.java`
    - Execute o programa com o comando: `java Main`
    - Ao rodar o programa, o usuário será solicitado a escolher um número de exercício de 1 a 15 para executar a funcionalidade correspondente.

3. **Exemplo de Entrada**:
    - Usuário escolhe o exercício, como por exemplo, `4` para realizar cálculos de área de formas geométricas.
    - O programa solicitará as entradas necessárias (como base, altura, etc.) e exibirá o resultado.

## Estrutura do Código

- **Scanner**: Para captura de entradas do usuário.
- **Switch-case**: Para navegação entre diferentes exercícios com base na escolha do usuário.
- **Laços**: Uso de laços `while` para controle de fluxo e contagens regressivas.

## Observações

- O código não possui validações de entrada para tipos de dados incorretos (como letras quando se espera um número), portanto, o usuário deve fornecer os dados corretamente.
- A divisão no **Exercício 8** não lida com divisões por zero, garantindo que o número divisor seja maior que zero.

## Licença

Este código é de uso livre para fins educacionais.
