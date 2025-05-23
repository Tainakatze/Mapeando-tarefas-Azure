# Mapeando-tarefas-Azure

Descrição
O Azure permite realizar diversas tarefas para apoiar aplicações, armazenar dados e criar infraestrutura. Neste desafio, você deverá associar tarefas comuns com os recursos do Azure que possibilitam essas ações.

Entrada
A entrada será uma das tarefas abaixo:

Criar um servidor com sistema operacional
Guardar dados em um banco relacional
Explorar os serviços disponíveis
Criar conta para acessar o Azure
Saída
A saída será o recurso correspondente:

Maquina Virtual
Instância de Banco de Dados
Portal Azure
Conta Microsoft e Assinatura
Exemplos
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

Entrada	Saída
Criar um servidor com sistema operacional	Maquina Virtual
Guardar dados em um banco relacional	Instância de Banco de Dados
Explorar os serviços disponíveis	Portal Azure
Atenção: É extremamente importante que as entradas e saídas sejam exatamente iguais às descritas na descrição do desafio de código.


# Recebe a entrada do usuário e armazena na variável "entrada":
entrada = input()

# Função responsável por receber um conceito e retornar sua respectiva descrição:
def identificar_recurso(tarefa):
  if tarefa == "Criar um servidor com sistema operacional":
    return "Máquina Virtual"

# COMPLETE AQUI: Preencha corretamente cada conceito, considerando as descrições abaixo: 
  elif tarefa == "Guardar dados em um banco relacional":
    return "Instância de Banco de Dados"
  elif tarefa == "Explorar os serviços disponíveis":
    return "Portal Azure"
  elif tarefa == "Criar conta para acessar o Azure":
    return "Conta Microsoft e Assinatura"

print(identificar_recurso(entrada))
