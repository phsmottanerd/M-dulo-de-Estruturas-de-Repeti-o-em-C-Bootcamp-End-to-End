# 📊 Módulo de Estruturas de Repetição em C# — Bootcamp End-to-End

![Badge Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)  
![Badge C#](https://img.shields.io/badge/C%23-Programação-blue)  
![Badge Bootcamp](https://img.shields.io/badge/Bootcamp-DIO-green)  
![Badge VS Code](https://img.shields.io/badge/Editor-VSCode-blueviolet)  
![Badge Plataforma](https://img.shields.io/badge/Plataforma-.NET-blue)

---

## 🚀 Sobre o Projeto

Este repositório contém os códigos desenvolvidos durante a prática do módulo **"Conhecendo as Estruturas de Repetição em C#"** do Bootcamp **End-to-End C#**, com duração de 2 horas (parte de um curso completo com 9 horas de conteúdo técnico).

Durante este módulo, explorei as estruturas básicas de repetição em C# e criei um **menu interativo de terminal** que simula funcionalidades simples de um sistema de cadastro de clientes. Também treinei a construção de laços `for`, `while` e `do while` com lógica aplicada de forma prática e didática.

---

## 🧠 Conceitos praticados

- `while` com menu interativo 📋  
- `switch case` com opções dinâmicas  
- Estrutura de repetição `for` para tabuada 🔢  
- Comando `do while` para somatório de números digitados  
- Leitura de dados com `Console.ReadLine()`  
- Escrita dinâmica com `Console.WriteLine()`  

---

## 🛠️ Tecnologias Utilizadas

- `C#` 💻
- `.NET Console` ⚙️
- `Visual Studio Code` 🧩
- `Terminal Interativo` 📟

---

using System;

class Program
{
    static void Main()
    {
        string opcao;
        bool exibirMenu = true;

        while (exibirMenu)
        {
            Console.WriteLine("Digite a sua opção:");
            Console.WriteLine("1- Cadastrar cliente");
            Console.WriteLine("2- Buscar cliente");
            Console.WriteLine("3- Apagar cliente");
            Console.WriteLine("4- Encerrar");

            opcao = Console.ReadLine();

            switch (opcao)
            {
                case "1":
                    Console.WriteLine("Cadastro de cliente");
                    break;
                case "2":
                    Console.WriteLine("Busca de cliente");
                    break;
                case "3":
                    Console.WriteLine("Apagar cliente");
                    break;
                case "4":
                    Console.WriteLine("Encerrar");
                    exibirMenu = false;
                    break;
                default:
                    Console.WriteLine("Opção inválida");
                    break;
            }
        }

        Console.WriteLine("O programa se encerrou");
    }
}
📁 Projeto 2 - Tabuada
Cálculo da tabuada do número 5 usando for.

Código:
csharp
Copiar
Editar
int numero = 5;
for (int contador = 0; contador <= 10; contador++)
{
    Console.WriteLine($"{numero} x {contador} = {numero * contador}");
}

📁 Projeto 3 - Soma com do while
Soma de números digitados até o usuário digitar 0.

Código:
csharp
Copiar
Editar
int soma = 0, numero = 0;
do
{
    Console.WriteLine("Digite um número:");
    numero = Convert.ToInt32(Console.ReadLine());
    soma += numero;
} while (numero != 0);

Console.WriteLine($"Total da soma dos números digitados é: {soma}");
👨‍💻 Desenvolvido por
Paulo Henrique Santana Motta ✨

markdown
Copiar
Editar

### ✅ Dicas para deixar mais organizado:

- Use `##` para seções principais.
- Use `###` ou `####` para subtítulos ou projetos internos.
- Pode até colocar divisores com `---` entre seções.

Se quiser, posso montar a estrutura toda com base em todos os códigos que você tiver. É só mandar!

