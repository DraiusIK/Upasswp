# Upasswp - passwords

Este código é escrito em C e tem como objetivo gerar senhas aleatórias com uma combinação de letras, números e símbolos. Ele pede ao usuário para inserir o número de senhas desejadas e o comprimento de cada senha. Utilizando as funções rand() e time(NULL) para gerar valores aleatórios, o código seleciona caracteres aleatórios das constantes ASCII_LETTERS, DIGITS e PUNCTUATION para criar as senhas. As senhas geradas são exibidas na tela. O código também verifica se o número e o comprimento são positivos, caso contrário, o programa é finalizado. Além disso, Ele utiliza algumas funções do string.h como strcpy e strcat para copiar e concatenar strings respectivamente, e função scanf para ler o input do usuário.
