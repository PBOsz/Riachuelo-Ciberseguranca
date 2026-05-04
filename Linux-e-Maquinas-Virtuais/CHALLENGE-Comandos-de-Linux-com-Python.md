<h1> CHALLENGE: Comandos de Linux com Python <h1>

<p>

Nesta lição, iremos realizar o desafio que foi proposto no curso.

Desafio
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

  Desafio 2
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
