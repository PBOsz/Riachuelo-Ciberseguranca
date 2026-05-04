<h1> CHALLENGE: Comandos de Linux com Python <h1>

<p>

Nesta lição, iremos realizar o desafio que foi proposto no curso.
<b> Desafio 1 Treinando Comandos de Linux com Python </b>
Na loja de roupas "Fashion Terminal", a equipe utiliza um sistema Linux para organizar o estoque e registrar vendas.
Certo dia, a gerente percebeu que muitos funcionários têm dúvidas sobre comandos básicos do terminal, especialmente ao listar arquivos de diferentes departamentos.
Para ajudar no treinamento, ela decidiu criar um simulador que recebe o nome de um comando Linux e retorna sua descrição funcional, facilitando o aprendizado dos colaboradores.
Sua tarefa é implementar um programa que, ao receber o nome de um comando Linux comum, retorne uma breve explicação sobre sua utilidade.
Caso o comando não seja reconhecido, o programa deve informar que o comando é invalido.

Implemente um programa que leia uma string representando o nome de um comando Linux e imprima a descrição correspondente.
Os comandos reconhecidos são:
ls (lista arquivos e diretorios)<br>
cd (altera o diretorio atual)<br>
pwd (mostra o caminho do diretorio atual)<br>
mkdir (cria um novo diretorio).<br>
Para qualquer outro comando, imprima "comando invalido".<br>
Não utilize bibliotecas externas.

Entrada<br>
Uma única string representando o nome de um comando Linux.

Saída<br>
Uma única string com a descrição do comando, ou "comando invalido" caso não seja reconhecido.
<img width="171" height="159" alt="image" src="https://github.com/user-attachments/assets/5347b87b-a1b1-4d58-b67f-ad7539304684" />

<pre>

  # Adicione no dicionário com comandos Linux e suas descrições
comandos = {
    "ls": 
    "cd": 
    "pwd": 
    "mkdir":  
}

# Lê o comando digitado pelo usuário
entrada = input().strip()

# Busca a descrição do comando ou informa se é inválido
descricao = comandos.get(entrada, "comando invalido")
print(descricao)
  
</pre>

<b> Desafio 2 Treinando Comandos de Linux com Python </b>
Desafio
Na loja de roupas FastWear, a equipe de vendas utiliza terminais Linux para registrar operações do estoque.
Recentemente, a gerente percebeu que muitos funcionários têm dúvidas sobre comandos básicos do sistema, o que atrasa o atendimento e a reposição de produtos.
Para resolver esse problema, ela decidiu criar um treinamento prático: cada funcionário deve identificar corretamente o comando
Linux apropriado para uma determinada tarefa do dia a dia na loja, como listar arquivos, criar diretórios para novas coleções ou remover itens antigos do estoque digital.
Sua missão é ajudar a gerente a automatizar esse treinamento, criando um programa que, ao receber uma descrição da tarefa, retorne o comando Linux correspondente.

Implemente um programa que leia uma string descrevendo uma tarefa comum em um terminal Linux na loja e retorne o comando Linux mais adequado para realizá-la.
Considere apenas tarefas básicas como listar arquivos, criar diretórios, remover arquivos e exibir o conteúdo de arquivos.
Se a tarefa não corresponder a nenhuma dessas, retorne "comando desconhecido". Não utilize bibliotecas externas.

Entrada<br>
Uma única linha contendo a descrição da tarefa a ser realizada no terminal Linux.

Saída<br>
Uma única linha com o comando Linux correspondente à tarefa ou "comando desconhecido" se não houver correspondência.

Exemplos
A tabela abaixo apresenta exemplos de entrada e saída:
Entrada	Saída:<br:
<img width="171" height="221" alt="image" src="https://github.com/user-attachments/assets/169cbe8f-92f0-4719-b0f2-f86f3a94f88e" />

<pre>

  # Adicione os comandos que presentão as ordem solicitadas 
comandos = {
    "listar arquivos": 
    "criar nova pasta": 
    "remover arquivo": 
    "mostrar conteudo": 
}

descricao = input().strip().lower()

comando_encontrado = "comando desconhecido"
for chave, comando in comandos.items():
    if chave in descricao:
        comando_encontrado = comando
        break  # Encontrou o comando, não precisa continuar

print(comando_encontrado)
  
</pre>

-------------------------------------------------------
Desafio 3 
Em uma empresa de tecnologia, o time de suporte está criando um treinamento rápido para novos colaboradores sobre métodos de autenticação.
Para reduzir erros no atendimento e reforçar boas práticas, cada participante deve identificar corretamente a descrição de um método ao receber seu nome.
Sua missão é implementar um programa que receba o tipo de autenticação e retorne a descrição correspondente.

Implemente um programa que leia uma string com o nome do método de autenticação e retorne sua descrição.
Considere apenas os conceitos: Senha, MFA, Biometria e Token. Não utilize bibliotecas externas.

Entrada
Uma única linha contendo o nome de um tipo de autenticação.

Saída
Uma única linha com a descrição correspondente ao tipo informado.

Exemplos
A tabela abaixo apresenta exemplos de entrada e saída:
<pre>
<img width="171" height="249" alt="image" src="https://github.com/user-attachments/assets/b304ca33-3b9e-4744-85c4-376cfd6a3902" />
  Preencha conforme o enunciado acima usando a lógica em Python.

  entrada = input()

def descrever_autenticacao(tipo):
    if tipo == "Senha":
        return "-------------"
    
    # TODO: complete as demais condições
    elif tipo == "MFA":
        return "-------------"
    
    elif tipo == "Biometria":
        return "-------------"
    
    elif tipo == "Token":
        return "-------------"

print(descrever_autenticacao(entrada))
  
</pre>

  Desafio 4
  Uma empresa sofreu incidentes simples por falta de padronização e decidiu reforçar boas práticas de segurança no dia a dia do time.
  Para isso, criou um treinamento automatizado: ao receber o nome de uma prática, o programa deve retornar sua descrição correta.
  Sua missão é implementar esse programa.
  Implemente um programa que leia uma string com o nome da prática e retorne a descrição correspondente.<br>
  Considere apenas: Backup, Atualização, Firewall e Antivírus.
  Não utilize bibliotecas externas.<br>

Entrada<br>
Uma única linha contendo o nome de uma prática de segurança.

Saída<br>
Uma única linha com a descrição correspondente à prática informada.

Exemplos
<pre>
A tabela abaixo apresenta exemplos de entrada e saída:
<img width="171" height="219" alt="image" src="https://github.com/user-attachments/assets/66db2bf1-4650-4577-93e6-eee6eced505d" />
  Preencha conforme o enunciado acima usando a lógica em Python.
  
  entrada = input()

def descrever_pratica(pratica):
    if pratica == "Backup":
        return "-------------"
    
    # TODO: complete as demais práticas
    elif pratica == "Atualizacao":
        return  "-------------"
    
    elif pratica == "Firewall":
        return  "-------------"
    
    elif pratica == "Antivirus":
        return "-------------"

print(descrever_pratica(entrada))
</pre>


<p>
