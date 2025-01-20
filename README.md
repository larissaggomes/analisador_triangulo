# Analisador de Triângulo

Este projeto é um exemplo de código em HTML e JavaScript que recebe as medidas de três lados de um triângulo e determina se é possível formar um triângulo, além de identificar se ele é equilátero, escaleno ou isósceles.
📋 Funcionalidades

    Solicita ao usuário os valores dos três lados do triângulo:
        Lado 1 (l1)
        Lado 2 (l2)
        Lado 3 (l3)

    Verifica se é possível formar um triângulo utilizando a condição:
    l1+l2>l3el2+l3>l1el1+l3>l2

    Verifica se o triângulo é:
        Equilátero: Todos os lados são iguais (l1 == l2 == l3).
        Escaleno: Todos os lados são diferentes (l1 != l2, l2 != l3, l1 != l3).
        Isósceles: Dois lados são iguais e um é diferente ((l1 == l2 && l1 != l3) || (l1 == l3 && l2 != l3) || (l2 == l3 && l1 != l3)).

    Exibe os resultados diretamente na página.

🚀 Como executar o código

    Salve o código em um arquivo com a extensão .html.
    Abra o arquivo em qualquer navegador.
    Digite os valores dos três lados quando solicitado.
    O programa exibirá:
        Se os lados podem formar um triângulo.
        Se o triângulo é equilátero, escaleno ou isósceles.

📌 Exemplo de Saída

Se o usuário fornecer:

    Lado 1: 5
    Lado 2: 5
    Lado 3: 5

A saída será:

Pode formar um triângulo: true
É um triângulo equilátero? true
É um triângulo escaleno? false
É um triângulo isósceles? false

🛠️ Tecnologias utilizadas

    HTML: Para a estrutura da página.
    JavaScript: Para as verificações lógicas e exibição dos resultados.

⚠️ Observações

    Certifique-se de inserir números válidos para os lados do triângulo.
    O código utiliza operadores lógicos para determinar a possibilidade de formar um triângulo e seu tipo.

📄 Licença

Este projeto é um exemplo didático e está disponível para uso e modificação livremente.
