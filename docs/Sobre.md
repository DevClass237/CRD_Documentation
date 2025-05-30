# Introdução :high_brightness:
A ideia deste projeto surgiu a partir de uma demanda da indústria, apresentada à turma pelo instrutor Samuel Teles. Após a decisão de desenvolver o projeto, o instrutor cadastrou a demanda na plataforma Saga SENAI de Inovação.

## Objetivo :dart:
Este projeto tem como objetivo atender à demanda da instituição SENAI-CETEC, promover melhorias contínuas no processo e na própria instituição, além de servir como Projeto de Conclusão de Curso da turma 2024.1.237.

## Descrição dos Componentes :electric_plug:
Arduino Mega 2560 - https://embarcados.com.br/arduino-mega-2560/ :round_pushpin:

Leitor RFID RC522 - https://mundoprojetado.com.br/modulo-rfid-rc522/ :round_pushpin:

Teclado Membrana ZRX-543 4x4 - https://www.usinainfo.com.br/teclado-matricial-e-buttons/teclado-matricial-membrana-4x4-16-teclas-2303.html :round_pushpin:

# Integração :link:
## Arduino :floppy_disk:
O Arduino recebe os dados lidos pelo leitor RFID, realiza a verificação com o banco de dados SQL, lê as entradas do teclado, realiza uma nova verificação e, após validação, envia os dados ao banco de dados via PlatformIO.

## Software :computer:
Foi utilizada a tecnologia Blazor, que permite desenvolver páginas web utilizando C#. O sistema lê os dados enviados ao banco de dados pelo Arduino, realiza atualizações e exibe as informações ao usuário de forma intuitiva.

## Modelo Físico :black_nib:
Para acomodar os componentes de hardware, foi desenvolvida uma estrutura em acrílico utilizando a ferramenta AutoCAD 2025. O modelo está anexado na documentação. Foram utilizadas duas placas de acrílico: uma de 5mm para a estrutura principal e outra de 3mm na parte do encaixe do teclado membrana. Esse encaixe foi projetado com duas placas sobrepostas para evitar que a espessura ficasse excessiva, caso fosse utilizada apenas a placa de 5mm.

## Instalação :hourglass_flowing_sand:
Em desenvolvimento. Instruções futuras incluirão: instalação do software, conexão de hardware, configuração do banco de dados e execução inicial.

## Organização :file_folder:
Versionamento de código: GitHub

Organização das tarefas: Trello, utilizando a metodologia Kanban

# Equipes :pray:
O projeto foi dividio em 4 equipes inicialmente posteriormente passando a ser 3.

Desenvolvimento de Software (C#) :globe_with_meridians:

• :woman: Dannyele Silva Teixeira

• :man: Willian Dias Marinho

Desenvolvimento em C++ :wrench:

• :man: João Victor Oliveira Dourado Costa

• :man: Wenerson Douglas Dos Santos Lima

Banco de Dados (SQL) :floppy_disk:

• :man: Iago Ferreira Cirino

• :man: Bruno Rodrigues Pajeu

• :man: Welson Ferreira de Carvalho

Modelagem Física :triangular_ruler:

• :man: Davi Fontinele de Sousa

• :man: Kaio Rodrigo Ferreira Dos Santos

Testes :sparkles:

• :man: Samuel Teles (Instrutor)

# Possiveis Melhorias :dizzy:
Incluir sugestões de melhorias futuras, como: integração com aplicativo mobile, implementação de dashboard de monitoramento, uso de sensores adicionais, entre outros.

# Conclusão :ok_hand:
Em desenvolvimento. Aqui deve ser apresentado um resumo dos resultados alcançados, principais aprendizados da equipe e a importância do projeto para a formação técnica e para a instituição.
