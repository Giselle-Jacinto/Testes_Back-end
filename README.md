# teste_backend
 
Começamos criando uma pasta e abrindo ela. Digitamos na parte do endereço "cmd" 1

Sem prompt de comando, digitamos "code ." (com o ponto separado) e pressionamos enter 2
no terminal digitamos dotnet new classlib -f net6.0 -o Operacoese pressionamos enter

Um projeto de aulas será criado. Agora, dentro da pasta Operacoes, renomeamos o arquivo Class1.cs para Operacoes.cs
Depois, vamos criar uma função somar
Agora vamos criar um projeto de testes. Para isso, usamos o comando dotnet new xunit -o Operacoes.xunit

Depois disso, precisamos apontar para o projeto de testes onde está o projeto de aulas. Para isso, usamos o comando dotnet add ./Operacoes.xunit/Operacoes.xunit.csproj reference ./Operacoes/Operacoes.csproj

Depois, na pasta Operacoes.xunit, abrimos o arquivo UnitTest1.cs Criamos a seguinte estrutura
Onde num1 e num2 são os números a serem somados, res o resultado esperado.

Para rodarmos o teste, precisamos entrar na pasta pelo terminal, já que atualmente ele está na pasta que vem antes. Para isso, usamos o comandocd Operacoes.xunit

Depois disso, usamos o comando dotnet test para fazermos o teste. 
Depois disso, rodamos o teste de novo com o comando dotnet test


