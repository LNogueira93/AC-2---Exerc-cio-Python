# 1800180 - Lucas Moises Nogueira
# 1800182 - Jady Pelissari Redini

# TODO: crie a função que recebe a pergunta e retorna a resposta do usuário

def pergunta(p):
  resposta = input(p)
  return resposta


# função que recebe uma lista com as respostas retorna a quantidade de respostas positivas. 
# complete a declaração e o corpo da função
# mas não altere o nome dessa função
def quantidade_sim(lista):
  lista = input(resposta)
repetidos = [0,1]
repetidos.count(1)


# função querecebe a quantidade de respostas positivas e retorna sua classificação
# complete a declaração e o corpo da função
# mas não altere o nome dessa função
#def classificacao():
  # remova o pass quando for escrever seu código

# para executar testes, mantenha if __name__ == '__main__':
# para executar sem os testes remova if __name__ == '__main__':
# faça seus testes aqui
# remova o pass quando for escrever seu código
r1 = pergunta('Telefonou para a vítima? ')
r2 = pergunta('Esteve no local do crime?')
r3 = pergunta('Mora perto da vítima?')
r4 = pergunta('Devia para a vítima?')
r5 = pergunta('Já trabalhou com a vítima?')

lista = [r1, r2, r3, r4, r5]
lista.append (r1)
lista.append (r2)
lista.append (r3)
lista.append (r4)
lista.append (r5)
lista = quantidade_sim (repetidos)


-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-_-


# 1800180 - Lucas Moises Nogueira
# 1800182 - Jady Pelissari Redini

# TODO: crie a função que recebe a pergunta e retorna a resposta do usuário

def pergunta(p):
  resposta = input(p)
  return resposta


# função que recebe uma lista com as respostas retorna a quantidade de respostas positivas. 
# complete a declaração e o corpo da função
# mas não altere o nome dessa função
def quantidade_sim(lista):
  lista = input(resposta)
repetidos = ['r1'+ 'r2' + 'r3' + 'r4'+ 'r5']
repetidos.count(1)


# função querecebe a quantidade de respostas positivas e retorna sua classificação
# complete a declaração e o corpo da função
# mas não altere o nome dessa função
#def classificacao():
  # remova o pass quando for escrever seu código

# para executar testes, mantenha if __name__ == '__main__':
# para executar sem os testes remova if __name__ == '__main__':
# faça seus testes aqui
# remova o pass quando for escrever seu código
r1 = pergunta('Telefonou para a vítima? ')
r2 = pergunta('Esteve no local do crime?')
r3 = pergunta('Mora perto da vítima?')
r4 = pergunta('Devia para a vítima?')
r5 = pergunta('Já trabalhou com a vítima?')

lista = []
lista.append (r1)
lista.append (r2)
lista.append (r3)
lista.append (r4)
lista.append (r5)
#lista = quantidade_sim (repetidos)
print("Resposta 1: ", r1)
print("Resposta 2: ", r2)
print("Resposta 3: ", r3)
print("Resposta 4: ", r4)
print("Resposta 5: ", r5)
print("Itens da lista", lista)
print ('Repetidos: ', repetidos.count[1])




___-----------------------------------------------------------------------------




question = ["Telefonou para a vítima?", "Esteve no local do crime?", "Mora perto da vítima?", "Devia para a vítima?", "Já trabalhou com a vítima?"]
answer = []
def questions(question):
  for x in range(len(question)):
    print(question[x])
    answer_x = input('1 = Sim/0 = Não: ')
    answer.append(answer_x)

  
def quantidade_sim(list):
  # remova o pass quando for escrever seu código
  count = 0
  for count in range(len(answer)):
    if answer[count] == '1' or answer[count] == 'Sim' or answer[count] == 'sim':
        count += 1
  return count
  

# função querecebe a quantidade de respostas positivas e retorna sua classificação
# complete a declaração e o corpo da função
# mas não altere o nome dessa função
def classificacao(count):
  # remova o pass quando for escrever seu código
  quantos = answer.count('1')

  classificacao = ""
  if quantos == 0:
    classificacao = "Inocente"
  elif quantos == 1:
    classificacao = "Inocente"
  elif quantos == 2:
    classificacao = "Suspeito"
  elif quantos == 3:
    classificacao = "Cúmplice"
  elif quantos == 4:
    classificacao = "Cúmplice"
  elif quantos == 5:
    classificacao = "Assasino"
  return classificacao

# para executar testes, mantenha if name == 'main':
# para executar sem os testes remova if name == 'main':
#if name == 'main':
  # faça seus testes aqui
  # remova o pass quando for escrever seu código

questions(question)
print (classificacao(quantidade_sim(answer)))

print ("Quantidade de SIM: ",answer.count('1'))
#quantos = answer.count('1')
#print("Quantos: ",quantos)

#if quantos == 0:
#    print ("Ele é Inocente")
#elif quantos == 1:
#    print ("Ele é Inocente")
#elif quantos == 2:
#    print ("Ele é Suspeito")
#elif quantos == 3:
#    print ("Ele é Cúmplice")
#elif quantos == 4:
#    print ("Ele é Cúmplice")
#elif quantos == 5:
#    print ("Ele é Assasino")
