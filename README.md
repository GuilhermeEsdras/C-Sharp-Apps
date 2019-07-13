<!-- Título do Respositório -->
# C Sharp Apps
<!-- -->

<!-- Badges -->
<p align="center">
    <img src="https://img.shields.io/badge/Linguagem-C%23-blue.svg?style=flat&colorB=9332ff" alt="this is purple">
</p>
<!-- -->

<br/>

<!-- Logo -->
<p align="center">
    <img src="https://camo.githubusercontent.com/0617f4657fef12e8d16db45b8d73def73144b09f/68747470733a2f2f646576656c6f7065722e6665646f726170726f6a6563742e6f72672f7374617469632f6c6f676f2f6373686172702e706e67" alt="C#" height="100">
</p>
<!-- -->

<!-- Subtítulo -->
<h2 align="center">My C# Repo! =)</h2>
<!-- -->

<!-- Msg de boas vindas -->
<p align="center">
    Bem-vindo ao meu repositório de <strong>C Sharp</strong>!
    <br/>
    <a href="https://docs.microsoft.com/pt-br/dotnet/csharp/language-reference/" target="_blank"><strong>Ver documentação da linguagem »</strong></a>
    <br/><br/>
    <a href="Exercícios Resolvidos">Exercícios Resolvidos</a>
    ·
    <a href="Programas">Programas</a>
    ·
    <a href="Projetos .NET">Projetos .NET</a>
</p>
<!-- -->

---

<!-- Table of Contents -->
## Glossário
- [C Sharp Apps](#C-Sharp-Apps)
  - [Glossário](#Gloss%C3%A1rio)
  - [Objetivo](#Objetivo)
  - [Material Utilizado](#Material-Utilizado)
    - [Sistema Operacional](#Sistema-Operacional)
    - [Compilador](#Compilador)
    - [IDE](#IDE)
  - [Programando em C Sharp](#Programando-em-C-Sharp)
    - [Pré-Requisitos](#Pr%C3%A9-Requisitos)
    - [Criando Projeto .NET](#Criando-Projeto-NET)
    - [Executando .cs pelo CMD](#Executando-cs-pelo-CMD)
    - [Exemplo de Código](#Exemplo-de-C%C3%B3digo)
  - [Links Úteis](#Links-%C3%9Ateis)
  - [Autor](#Autor)
  - [Licença](#Licen%C3%A7a)
<!-- -->

<!-- Objetivo -->
## Objetivo
Este repositório foi criado com a finalidade de guardar meus projetos, ideias, anotações, exercícios e programas pessoais feitos em <strong>C#</strong>.
<!-- -->

<!-- Material Utilizado -->
## Material Utilizado
Estes são os materiais usados por mim para desenvolver e rodar meus programas em C#.
### Sistema Operacional
- [Windows 10](https://www.microsoft.com/pt-br/windows/)
### Compilador
- [CSC](#Links-%C3%9Ateis)
### IDE
- [Visual Studio Code](https://code.visualstudio.com/)
<!-- -->

<!-- Programando em C Sharp-->
## Programando em C Sharp
O que foi necessário para criar e rodar programas em C#

### Pré-Requisitos
Para executar e criar programas em **C#** é necessário ter a plataforma Microsoft .NET (*dot net* em inglês) Core SDK *(Software Development Kit)* instalada no computador.

- Para verificar se o .NET está instalado no PC, basta executar o comando no CMD: <br/>
    `> dotnet`
> - Se o comando não for reconhecido, **não está** instalado! *(ver [Links Úteis](#Links-%C3%9Ateis) para instalar o .NET)* <br/>
> - Caso apareça outras mensagens, **está** instalado! <br/>

### Criando Projeto .NET
- Para criar um projeto C# com .NET, executar o comando: <br/>
`> dotnet new console -o "nome do projeto"`

  - Exemplo: <br/>
    `> dotnet new console -o meuProjeto`

> - Será criada uma pasta com o nome do projeto escolhido
> - Dentro da pasta terão dois arquivos: 
>   - *"nome do projeto".csproj* e *Program.cs*
> - e duas pastas: 
>   - */bin* e */obj*

- Para criar e editar códigos em C#:
  - Abrir arquivos com a extensão "*.cs*"

- Para executar um programa em C#:
  - Abrir um terminal/CMD na pasta onde se localiza o arquivo *.cs* principal/main e executar o comando: <br/>
  `> dotnet run`

### Executando .cs pelo CMD
Criando e executando um programa isolado/simples em C# pelo CMD (sem necessidade de criar projeto ou abrir Visual Studio)

1. Para executar arquivos *.cs* pelo terminal deve-se ter o compilador *"csc"* devidamente configurado no PC.

2. Após certifica-se de ter instalado o *.NET*, copiar o endereço da pasta da versão mais recente do mesmo. Geralmente localiza-se em:
  `C:\Windows\Microsoft.NET\Framework64\"pasta da versão mais recente"`
     - Exemplo:
     `C:\Windows\Microsoft.NET\Framework64\v4.0.30319`

3. Após copiar, ir até as Configurações Avançadas do Sistema *(Botão direito em cima de "Este Computador" -> Lado superior esquerdo)*
   
4. Clicar em Váriaveis de Ambiente -> PATH -> Novo -> Inserir o endereço da pasta no fim da linha das variáveis do sistema.
   
5. Finalmente, será capaz de compilar e executar programas C# pelo terminal.

- Para compilar programas *".cs"* e executá-los no terminal/cmd:
  - Abrir pasta onde se localiza o arquivo *.cs*: <br/>
     `> cd "pasta do programa"`
  - Compilar o programa: <br/>
     `> csc "nome do programa".cs // Será gerado um arquivo "nome do programa".exe`
  - Para executar: <br/>
     `> "nome do programa".exe`
  
  - Exemplo: <br/>
     `> cd "C:\Users\Fulano\Documentos\Meus Programas\CSharp\Programa Hello World" // Para ir até a pasta do arquivo .cs` <br/>
     `> csc HelloWorld.cs // Para compilar um programa chamado "HelloWorld"` <br/>
     `> HelloWorld.exe // Para executar este programa`

### Exemplo de Código
``` C#
using System;

namespace HelloGui
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello Gui! =)");
        }
    }
} 
```

Saída:

`> Hello Gui! =)`
<!-- -->

<!-- Links-->
## Links Úteis
- [Tutoriais e instalação do Microsoft .NET SDK](https://dotnet.microsoft.com/learn/dotnet/hello-world-tutorial/install)
- [Comandos do compilador CSC](https://docs.microsoft.com/pt-br/dotnet/csharp/language-reference/compiler-options/command-line-building-with-csc-exe)
<!-- -->

<!-- Autor/Contato -->
## Autor
* **Guilherme Esdras (guilherme.esdras@outlook.com)** - [GitHub Page](https://github.com/GuilhermeEsdras)
<!-- -->

<!-- Licença -->
## Licença
*Distributed under the MIT License. See LICENSE for more information.*