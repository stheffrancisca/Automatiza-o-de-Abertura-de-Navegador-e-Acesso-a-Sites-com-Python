# Automatiza-o-de-Abertura-de-Navegador-e-Acesso-a-Sites-com-Python
Este repositório demonstra como automatizar a abertura de um navegador e o acesso a um site específico usando Python. Através da combinação de bibliotecas como keyboard e time, o script simula a digitação de comandos no teclado para abrir o Google Chrome e navegar até uma URL desejada. É uma solução simples para automatizar tarefas repetitivas de navegação, ideal para iniciantes em automação com Python.


import keyboard
import time

keyboard.press_and_release("win")
time.sleep(1)
keyboard.write("chrome")

keyboard.press_and_release("enter")
time.sleep(1)
keyboard.write('https://www.google.com/')

keyboard.press_and_release('enter')
