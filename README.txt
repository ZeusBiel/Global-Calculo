Gabriel Oliveira Rodrigues

Para o codigo funcionar, tenha certeza de que matplotlib esteja instalado na sua maquina.

O projeto consiste da criação de uma API para consultar exames, informações uteis de clinicas e contato usando python para acessa-la.
Entre as centenas de dados disponiveis, ele filtra todas as datas, onde o exame foi finalizado e entregue, junto com o tipo de exame.
Neste exemplo estes dados foram filtrados pela API porém refeitos para que o exame não tenha importancia, ja que a amostra de dados seria muito pequena,
assim podendo identificar seus pontos de máximas e minimas.
A finalidade deste gráfico é apresentar a distribuição dos exames por tipo e tempo de espera, com uma base de dados de milhares de exames ao longo do ano,
e exibir em qual época do ano o tempo de espera é menor, além de comparar estes tempos com outras clinicas.

Exemplo:
+---------------------+---------------------+---------------------+
| Exame               | Finalizado          | Entregue            |
+---------------------+---------------------+---------------------+
| colesterol          | 16:10, 13/11/2023   | 17:25, 15/11/2023   |
| colesterol          | 11:20, 15/11/2023   | 12:45, 17/11/2023   |
| colesterol          | 14:15, 16/11/2023   | 15:30, 18/11/2023   |
| colesterol          | 15:30, 16/11/2023   | 16:45, 18/11/2023   |
| colesterol          | 18:17, 16/11/2023   | 19:32, 18/11/2023   |
| colesterol          | 11:30, 17/11/2023   | 12:55, 19/11/2023   |
| colesterol          | 14:45, 17/11/2023   | 16:22, 19/11/2023   |
| colesterol          | 10:05, 18/11/2023   | 11:20, 20/11/2023   |
| colesterol          | 14:50, 18/11/2023   | 16:05, 20/11/2023   |
| colesterol          | 09:15, 19/11/2023   | 10:40, 21/11/2023   |
| colesterol          | 08:50, 20/11/2023   | 10:15, 22/11/2023   |
| colesterol          | 13:20, 21/11/2023   | 15:00, 23/11/2023   |
| colesterol          | 16:45, 22/11/2023   | 18:30, 24/11/2023   |
+---------------------+---------------------+---------------------+
*Dados já modificados*

