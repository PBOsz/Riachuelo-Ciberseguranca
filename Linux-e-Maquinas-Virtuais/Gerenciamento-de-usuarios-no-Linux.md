<h1> Gerenciamento de usuários no Linux <h1>

<p>

Nesta lição iremos realizar o gerenciamento de usuários dentro do linux. Assim como windows o linux também pode ser criado usuários para acesso a máquina, tanto na interface GUI quanto via CLI.
Abordaremos a seguir a criação e administração de usuários via terminal (CLI), devido a ser CLI pode ser aplicado também para as distribuições linux server.

O comando básico para a criação do user é
<pre >useradd NomeDoUsuario</pre>
Com o comando "useradd" vai criar um usuário com o nome que quiser.

Agora, após criar esse user precisamos adicionar uma senha para que possa acessar o perfil, para isso usaremos o comando.
<pre>passwd NomeDoUsuario</pre>

O comando "passwd" precisa ser executado como root caso você precise trocar a senha de um usuário terceiro.

Geralmente, nos ambientes de 

<p>
