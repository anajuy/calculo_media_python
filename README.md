📚 Sistema de Notas do Aluno
 Descrição

O Sistema de Notas do Aluno é um programa desenvolvido em Python com o objetivo de calcular a média final de um aluno a partir de duas notas.

Após realizar o cálculo, o sistema informa automaticamente se o aluno foi APROVADO ou REPROVADO, considerando a média mínima de 7,0 pontos para aprovação.

🛠️ Tecnologias Utilizadas

Este projeto foi desenvolvido utilizando:

Python 3
input() para receber as notas do usuário
float() para trabalhar com números decimais
Funções para organizar o código
Estrutura condicional if/else
F-strings para apresentar os resultados
 Estrutura do Projeto
sistema-notas/
│
├── sistema_notas.py
└── README.md
 sistema_notas.py
Arquivo principal que contém todo o código responsável pelo funcionamento do sistema.
 README.md
Arquivo que apresenta informações sobre o projeto, instalação, execução e exemplos de utilização.

 Como Instalar
1. Instale o Python
Para executar o projeto, é necessário ter o Python 3 instalado no computador.
Depois da instalação, abra o terminal e verifique se o Python está funcionando:
python --version
Caso o comando acima não funcione, tente:
python3 --version
 Como Executar o Projeto
1. Abra o projeto no VS Code
Abra a pasta do projeto no Visual Studio Code.
2. Abra o terminal
No VS Code, utilize:
Ctrl + `
ou acesse:
Terminal → New Terminal
3. Execute o programa
Digite:
python sistema_notas.p
Se necessário:
python3 sistema_notas.py

 Código do Projeto
def calcular_media(nota1, nota2):
    return (nota1 + nota2) / 2


print("=== Sistema de Notas do Aluno ===")

n1 = float(input("Digite a primeira nota: "))
n2 = float(input("Digite a segunda nota: "))

media = calcular_media(n1, n2)

print(f"A média final é: {media:.2f}")

if media >= 7.0:
    print("Status: APROVADO!")
else:
    print("Status: REPROVADO.")

📊 Como o Sistema Funciona

O programa segue algumas etapas:

O usuário inicia o programa.

O sistema solicita a primeira nota.

O sistema solicita a segunda nota.

As notas são armazenadas nas variáveis n1 e n2.

A função calcular_media() calcula a média das duas notas.

O resultado é apresentado com duas casas decimais.

O sistema verifica se a média é maior ou igual a 7,0.

Se for maior ou igual a 7,0, o aluno é APROVADO.

Caso contrário, o aluno é REPROVADO.

🧮 Cálculo da Média

A média é calculada através da seguinte fórmula:

média = (nota1 + nota2) / 2


Por exemplo:

Nota 1 = 8
Nota 2 = 7

Média = (8 + 7) / 2
Média = 7,5


Como a média é maior ou igual a 7,0, o aluno será aprovado.

✅ Exemplo de Aluno Aprovado
Entrada
=== Sistema de Notas do Aluno ===
Digite a primeira nota: 8
Digite a segunda nota: 7

Saída
A média final é: 7.50
Status: APROVADO!

❌ Exemplo de Aluno Reprovado
Entrada
=== Sistema de Notas do Aluno ===
Digite a primeira nota: 5
Digite a segunda nota: 6

Saída
A média final é: 5.50
Status: REPROVADO.

🖼️ Demonstração

Você pode adicionar aqui uma captura de tela do programa funcionando.

Por exemplo:

![Demonstração do Sistema](./imagem.png)


Para isso, coloque uma imagem dentro da pasta do projeto:

sistema-notas/
│
├── sistema_notas.py
├── README.md
└── imagem.png


Depois, a imagem aparecerá no README quando ele for visualizado no GitHub.

🎯 Objetivo do Projeto

Este projeto foi desenvolvido com o objetivo de praticar conceitos básicos de programação em Python, como:

Variáveis

Entrada de dados

Conversão de tipos

Funções

Operações matemáticas

Estruturas condicionais

Formatação de texto

Organização de projetos

Possíveis Melhorias Futuras

Algumas funcionalidades podem ser adicionadas futuramente:

Adicionar mais notas.

Calcular a média de vários alunos.

Criar um cadastro de alunos.

Mostrar a maior e a menor nota.

Criar uma interface gráfica.

Armazenar os resultados em um arquivo.

Criar diferentes situações de aprovação.

Adicionar validação para impedir notas inválidas.

Autor

Nome: ANA JULIA

Curso: ADS

Projeto: Sistema de Notas do Aluno

 Contato

E-mail: ANAJULIA.SILVALIMA58@GMAIL.COM

GitHub:https://github.com/anajuy

