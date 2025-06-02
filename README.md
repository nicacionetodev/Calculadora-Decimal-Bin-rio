# Calculadora-Decimal-Binario
Bibliotecas Utilizadas no Projeto
projeto de calculadora de conversão numérica utiliza principalmente duas bibliotecas Python para construir a interface gráfica e gerenciar os dados.

1.customtkinter
Importação no Código: import customtkinter as ctk

Isso significa que você vai usar a biblioteca customtkinter e se referir a ela como ctk (um apelido comum para economizar digitação).
O que é: customtkinter é uma extensão moderna para o tkinter (que é a biblioteca gráfica padrão do Python). Ele foi criado para resolver alguns dos problemas visuais do tkinter original, que muitas vezes parece um pouco "datado" ou "antigo".
Bem-vindo à sua Calculadora de Conversão Numérica! Este é um aplicativo simples e intuitivo desenvolvido em Python com customtkinter, que permite converter números entre as bases decimal e binária usando uma interface de botões amigável.
Pré-requisitos: Certifique-se de ter o Python instalado (versão 3.x recomendada).

Instalação do customtkinter: Se você ainda não tem, instale a biblioteca customtkinter via pip:

Bash

pip install customtkinter
Executar o Aplicativo: Salve o código-fonte da calculadora em um arquivo .py (por exemplo, conversor.py) e execute-o via terminal:

Bash

python conversor.py

2.tkinter (Subjacente ao customtkinter)
Importação no Código: Embora você não importe tkinter diretamente com import tkinter, ele é a base do customtkinter. customtkinter utiliza o tkinter "por baixo dos panos" para todas as funcionalidades básicas de criação de janelas, widgets e eventos.

O que é: tkinter é a biblioteca padrão de Python para criar interfaces gráficas de usuário (GUIs). Ela já vem instalada com o Python, então você não precisa instalá-la separadamente.

Para que é Usado no Projeto (Indiretamente, via customtkinter):

Fundação da GUI: Todas as operações fundamentais de uma interface, como criar janelas, gerenciar eventos (cliques de botão, digitação), posicionar widgets (.grid()), e manipular variáveis de controle (StringVar), são, em sua essência, funcionalidades do tkinter que o customtkinter aprimora.
Gerenciamento de Layout (.grid()): O sistema de grade (.grid()) que você usa para organizar
