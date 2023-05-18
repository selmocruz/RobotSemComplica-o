# RobotSemComplica-o
 Teste automatizado com robot framework
 
Processos para instalação do Robot Framework
Instalando as dependências

Python
1. Faça download do Python de acordo com seu sistema operacional, atente-se para baixar a última versão. https://www.python.org/downloads/
python --version para confirmar a instalação

obs: uma observação importante que não podemos esquecer, durante a instalação marcar Add pyton.exe TO path
caminho da variável de ambiente, para podermos utilizar o python pela linha de comando 

Robot Framework
2. Instale o robot com o comando: pip install robotframework, através do terminal cmd
robot --version, para conferir a instação

Selenium
3. Instale o Selenium com o comando: pip install --upgrade robotframework-seleniumlibrary
para baixar essas dependências, bibliotecas

Browser
4. Para acessar o site de teste usaremos o browser Chrome, para isso é necessário instalar o driver do mesmo. O objetivo do driver é emular, o mais próximo possível, a interação de um usuário real com o navegador.Observação: Instalae o driver de acordocom a versão do navegador

VSCode
5. Faça download do VSCode de acordo com seu sistema operacional
instalar extensão python e robot no VSCode

Browser
6.Para acessar o site de teste usaremos o browser Chrome, para isso é necessário instalar o driver do mesmo. O objetivo do driver é emular, o mais próximo possível, a interação de um usuário real com o navegador.
Observação: Instalae o driver de acordo com a versão do navegador


Além de instalar o driver é preciso mapear o caminho do driver na variável de ambiente PATH.


Rodar os testes

1. Na linha de comando: robot -d result chronos.robot 

-d para mostrar onde que eu quero que meus relatórios estão indo, 
.\result o nome do meu diretório e o nome do arquivo robot que eu quero que execute













