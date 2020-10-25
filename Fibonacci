def calcular_fibonacci(i):
    
    if i == 0:
        return 0
    
    elif i == 1:
        return 1
    
    else:
        return calcular_fibonacci(i-1) + calcular_fibonacci(i-2)
            
def entrada_datos():
    print("Ingrese el numero inicial:")
    return int(input())


def main():    

    numero_inicial = entrada_datos()
    print('Secuencia fibonacci:')
    secuencia = []
    i = 0
    while(i != (numero_inicial+1)):
        secuencia.append(calcular_fibonacci(i))
        i += 1
        
    print(secuencia)
    
if __name__ == "__main__":
    main()
    
