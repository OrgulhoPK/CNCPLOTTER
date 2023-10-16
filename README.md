# CNCPLOTTER
Impressora CNC com caneta, utilizando motorshield e arduino

Programas necessários:
- Arduino IDE (Utilizado para programar o Arduino com o Motorshield)
- Inkscape (Necessário para gerar o arquivo GCode, apartir de um PNG)
- Processing (Utilizado a versão 3.5.4)( Necessário para enviar os comandos do GCode para o arduino configurado)

Slides com passo a passo de como montar a impressora, no link:

- https://www.canva.com/design/DAFuiTjEP2M/JYTvOA8e_r8fMpAcpDeQSA/edit?utm_content=DAFuiTjEP2M&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

- O arquivo servo_test é para testar a rotação do eixo z(servo motor)

 1- O arquivo na pasta CNC_code, está o código de pré configuração do arduino, com o motor-shield L293D. Abra o software do arduino, e faça upload para a placa.

 2- Agora vamos configurar o software Inkscape. Para isso, baixe e instale este software através do link abaixo.
  Inkscape: https://inkscape.org/release/inkscape-0.48/?latest=1

3- Em seguida, inclua a extensão do código G no software. Para isso, use os arquivos da pasta "G-code extention" insira-o na pasta de extensão de instalação do software Inkscape. (slide 22)

4- Para vetorizar a imagem, e gerar o arquivo .gcode, siga o passo a passo dos slides 23 a 32.

5- Ok, vamos executar o arquivo de código G-code. Para isso, baixe e instale o 
Processing IDE.
Processing IDE: https://processing.org/download/

6- Abra o arquivo na pasta processing_code e siga os passos dos slides 33 a 35.


