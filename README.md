<h1>Como fazer um phising para pegar senhas do Facebook usando Kali Linux</h1>
<br>
<h3>Serve para qualquer site colcoando o desejado no 'site cloner'</h3>
<br><br>
<h2>Explicação</h2>
Primeiramente, devemos logar com usuário root no terminal, para isso escrevemos sudo su, logo após, será solicitada a senha
<br>
selecionar o tipo de ataque, no nosso caso é social-engineering attacks
<br>
aqui, de onde via partir o ataque, nesse caso será website attack vector
<br>
após a explicação dada no terminal pelo kali, selecionaremos credential harvester attack mode para a colheita de credenciais
<br>
selecionaremos o modo que queremos, que no caso é site cloner
<br>
então, é pedido um servidor, basta apertar enter para confirmar
<br>
agora, informar a url, nesse caso é http://www.facebook.com, não pode ter o s no http
<br>
irá criar toda a wstrutura idêntica a do facebook para acessar
<br>
para poder acessar, basta colocar o ip da máquina do kali linux
<br>
entrando na página clonada, o terminal começa a reportar o que o acesso está fazendo
<br>
quando tenta logar, dá um loop direcionando para a página verdadeira
<br>
então, voltando no terminal na máquina kali aparece o "POSSIBLE USERNAME..." e "POSSIBLE PASSWORD..." com o usuário e senha que a vítima colocou no site clonado
<br><br>
<h2>Comandos no terminal</h2>
sudo su
<br>
***inserir a senha***
<br>
setoolkit
<br>
1
<br>
2
<br>
3
<br>
2
<br>
***enter***
<br>
http://www.facebook.com
<br>