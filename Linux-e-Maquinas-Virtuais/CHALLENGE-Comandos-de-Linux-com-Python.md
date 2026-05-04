<h1> CHALLENGE: Comandos de Linux com Python <h1>

<p>

Nesta lição, iremos realizar o desafio que foi proposto no curso.
O desafio é o seguinte:

Desafio
Em uma empresa de tecnologia, o time de suporte está criando um treinamento rápido para novos colaboradores sobre métodos de autenticação. Para reduzir erros no atendimento e reforçar boas práticas, cada participante deve identificar corretamente a descrição de um método ao receber seu nome. Sua missão é implementar um programa que receba o tipo de autenticação e retorne a descrição correspondente.

Implemente um programa que leia uma string com o nome do método de autenticação e retorne sua descrição. Considere apenas os conceitos: Senha, MFA, Biometria e Token. Não utilize bibliotecas externas.

Entrada
Uma única linha contendo o nome de um tipo de autenticação.

Saída
Uma única linha com a descrição correspondente ao tipo informado.

Exemplos
A tabela abaixo apresenta exemplos de entrada e saída:
<pre>
|--------------------------------------------------------------|
| Entrada   | Saída                                            |
|--------------------------------------------------------------|
| Senha	    | Combinacao secreta usada para acessar sistemas   |
| MFA	     | Uso de dois ou mais fatores de verificacao       |
| Biometria |	Identificacao baseada em caracteristicas fisicas |
| Token	    | Codigo temporario para validacao de acesso       |
| -------------------------------------------------------------|
<pre>


Preencha conforme o enunciado acima e lógica em Python.
<pre>

  entrada = input()

def descrever_autenticacao(tipo):
    if tipo == "Senha":
        return "Combinacao secreta usada para acessar sistemas"
    
    # TODO: complete as demais condições
    elif tipo == "MFA":
        return "Uso de dois ou mais fatores de verificacao"
    
    elif tipo == "Biometria":
        return "Identificacao baseada em caracteristicas fisicas"
    
    elif tipo == "Token":
        return "Codigo temporario para validacao de acesso"

print(descrever_autenticacao(entrada))
  
</pre>

<p>
