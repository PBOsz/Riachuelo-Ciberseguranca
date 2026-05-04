<h1> Manipulação de Arquivos no Linux <h1>

<p>

Nesta lição vamos realizar a manipulação de arquivos dentro do nosso querido linux.

Vamos fazer o acesso em nossa máquina virtual criada anteriormente, para fins de facilidade, irei utilizar o PowerShell via ssh para o servidor linux.
  *Como já falamos disso em outra lição não entraremos nesse assunto novamente, favor revisar caso previse em <a href="https://github.com/PBOsz/Riachuelo-Ciberseguranca/blob/main/Linux-e-Maquinas-Virtuais/Acesso-Remoto">Acesso Remoto</a>*

No usuário root faremos os comandos para conhecermos, lembrando que TODO comando no linux é case sensitive ou seja, ele deve ser digitado da maneira minuscula (todo comando é em minusculo), raro os caso que não.

Vamos iniciar com o mais básico de todos, ver o dia e horário atual do sistema, para isso usamos o comando:
date
*não precisa ser root*
A saída esperada é:
<pre>
 root@ubuntu-dio:~# date
qua 22 abr 2026 04:27:25 UTC
root@ubuntu-dio:~#"
</pre>
O próximo comando que vamos ver é a limpeza da tela, usamos o seguinte:
<pre>
clear
</pre>
Com ele, limpamos o nosso terminal caso tenha muito conteúdo que não faz mais sentido vermos, ele vai limpar a tela inteira, então caso tenha algo que precisa na tela tenha ciencia que ele vai limpar.<br>
\*Um atalho legal para usarmos é o seguinte: CRTL-Esquerdo + L essa combinação de teclas também vai limpar o terminal para você\*


Vamos falar agora sobre as permissões no sistema do linux, com um comando simples para ver as permissões vamos exemplificar.
<pre>ls -l</pre>
Com esse comando a saída esperada é:
<pre>┌─[live@parrot]─[~]
└──╼ $ls -l
total 0
drwx------ 2 live live  80 May  4 16:01 Desktop
drwx------ 2 live live  60 May  4 16:00 Documents
drwx------ 2 live live  40 May  4 16:00 Downloads
drwx------ 2 live live  40 May  4 16:00 Music
drwx------ 2 live live  40 May  4 16:00 Pictures
drwx------ 2 live live 580 May  4 16:00 Templates
drwx------ 2 live live  40 May  4 16:00 Videos
┌─[live@parrot]─[~]
└──╼ $</pre>
Veja, que nos temos letras estranhas ao lado esquerdo dos diretorios... Essas letras são o que indica as permissões, isso é mostrado devido ao argumento "-l".
Temos 3 colunas de permissões, no qual a primeira letra mostra se é diretorio ou não, evidenciado pela letra "d" no começo.<br>
drwx------ 2 live live  80 May  4 16:01 Desktop


<p>
