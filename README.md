# Projeto: Censura de imagem bitmap em assembly
Universidade Federal da Paraíba - UFPB  
Centro de Informática  
**Autores:** João Victor Lourenço da Silva (20220005997), Eliane Santos Silva (20220155152)  

## Criação de programa assembly, no Nasm32, para obtenção de nota na disciplina de Arquitetura de Computadores.

### Sobre o projeto:

Neste projeto, o programa funciona da seguinte forma:

- Recebe o nome de um arquivo (no formato .bmp);
- Recebe um valor X;
- Recebe um valor Y;
- Recebe um valor de largura;
- Recebe um valor de altura;
- Recebe um nome para um arquivo de saída (aplicando .bmp no fim).

Após receber estas entradas, o programa lê o arquivo de entrada (linha por linha) e escreve no arquivo de saída. Contudo, no arquivo de saída, os pixels de Y até Y+altura-1 e de X até X+largura-1 serão modificados para 0, criando um tipo de "censura" no arquivo de saída. Ou seja, o programa deve iniciar a leitura de linhas e, quando chegar na linha Y, deve chamar uma função para realizar a censura.

#### OBS:
- Deve haver a tratativa correta de bytes e pixels;
- As censuras devem ser aplicadas por meio de funções;
- Deve-se usar uma pilha para passar parâmetros para a função de censura.
