-----------------------------------------------------
# List Lesson

## Exercício 1: Adicionar um elemento a uma lista

numeros = [1, 2, 3, 4, 5]

numeros.append (6) # Adicionar o 6 na lista
numeros.insert(0, 0) # Adicionar 0 no começo

print(numeros)


## Exercício 2: Remover um elemento a uma lista

numeros = [1, 2, 3, 4, 5]

numeros.remove (3) # Remove o número 3 da lista
numeros.pop()  # Remove o último elemento da lista

print(numeros)


## Exercício 3: Substituir um elemento a uma lista

numeros = [10, 20, 30, 40, 50]

numeros[2] = 35
numeros[4] = 55

print(numeros)


## Exercício 4: Ordene uma lista

numeros = [2, 5, 3, 1, 4]

numeros.sort() # Para deixar descrecente 'numeros.sort(reverse=True)'

print(numeros)


## Exercício 5: Verificar se um elemento está na lista

verificador = int(input("Digite um número para verificar se ele está na lista: "))

numeros = [1, 2, 3, 4, 5]

if verificador in numeros:
    print(f"O número {verificador} está na lista.")      
else:
    print(f"O número {verificador} não está na lista.")
    
-----------------------------------------------------
# Tupla Lesson

## Exercício 1:
