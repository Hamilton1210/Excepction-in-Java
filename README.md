# Excepction-in-Java

Quando se cria programas de computador em Java, há possibilidade de ocorrer erros imprevistos durante sua execução, esses erros são conhecidos como exceções e podem ser provenientes de erros de lógica ou acesso a dispositivos ou arquivos externos.


Em que situações podem occorrer exceções em Java?

As exceções ocorrem quando algo imprevisto acontece, elas podem ser provenientes de erros de lógica ou acesso a recursos que talvez não estejam disponíveis.

Alguns possíveis motivos externos para ocorrer uma exceção são:

Tentar abrir um arquivo que não existe.
Tentar fazer consulta a um banco de dados que não está disponível.
Tentar escrever algo em um arquivo sobre o qual não se tem permissão de escrita.
Tentar conectar em servidor inexistente.


Alguns possíveis erros de lógica para ocorrer uma exceção são:

Tentar manipular um objeto que está com o valor nulo.
Dividir um número por zero.
Tentar manipular um tipo de dado como se fosse outro.
Tentar utilizar um método ou classe não existentes.


POSSIVEIS SOLUÇÕES:

Uma maneira de tentar contornar esses imprevistos é realizar o tratamento dos locais no código que podem vir a lançar possíveis exceções, como por exemplo, campo de consulta a banco de dados, locais em que há divisões, consulta a arquivos de propriedades ou arquivos dentro do próprio computador.

Para tratar as exceções em Java são utilizados os comandos try e catch.
 (...)

