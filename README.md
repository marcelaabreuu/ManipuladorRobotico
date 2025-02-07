Este trabalho foi realizado no UAIBot, o qual é um simulador robótico baseado na web desenvolvido por Vinicius Mariano Gonçalves (Departamento de Engenharia Elétrica, Universidade Federal de Minas Gerais, Brasil) e seus alunos.
https://github.com/UAIbot/UAIbotPy

É mais fácil começar a usar o UAIBot em um navegador da web. Vamos usar o GoogleColab, pois ele nos permite executar código Python em um navegador.

Abra um novo notebook. Agora, precisamos instalar o UAIBot nos servidores do GoogleColab. Isso pode ser feito simplesmente executando os seguintes comandos:

!pip install uaibot 

Após a instalação, testamos se está funcionando executando o seguinte comando.

import uaibot as ub

sim = ub.Demo.control_demo_1()

################# English ###################################

This program was carried out on UAIBot, a web-based robotic simulator developed by Vinicius Mariano Gonçalves (Department of Electrical Engineering, Federal University of Minas Gerais, Brazil) and his students.

https://github.com/UAIbot/UAIbotPy

It is easier to start using UAIBot in a web browser. We will use GoogleColab since it allows us to run Python code in a web browser.

Open a new notebook. Now, we need to install UAIBot in the GoogleColab servers. This can be done by simply running the following commands:

!pip install uaibot

After it is done, we test if it is working by running the following command

import uaibot as ub

sim = ub.Demo.control_demo_1()
