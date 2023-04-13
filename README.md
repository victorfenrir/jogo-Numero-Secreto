# jogo-Numero-Secreto

Projeto do curso de Reconhecimento e Validação com Voice API da escola de Front-End da Alura.

Este jogo deve ser jogado utilizando microfone para que haja o reconhecimento de voz.
Ao iniciar, um número secreto de 0 a 1000 será aleatóriamente gerado. Tente adivinhar.

O jogo às vezes não reconhece números pequenos (abaixo de 100) pois ao invés de reconhecer,
por exemplo, você falar o número 10 e escrevê-lo assim, ele escreve por extenso, retornando como valor inválido.
Melhorias serão realizadas em algum momento.
Se o número que está tentando tiver ao menos duas casa decimais, é possível contornar a situação
ao "quebrar" esse número em digitos, por ex: para que o jogo entenda 69 (sessenta e nove), às vezes será
necessário dizer "Seis Nove" ou "Meia Nove".

Em caso de acerto, poderá reiniciar o jogo clicando no botão "Jogar novamente".
