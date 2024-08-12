# calculadora.py
calculadora.py
def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y == 0:
        return "Erro! Divisão por zero."
    return x / y

def calculator():
    print("Selecione a operação:")
    print("1 - Soma")
    print("2 - Subtração")
    print("3 - Multiplicação")
    print("4 - Divisão")
    
    while True:
        choice = input("Escolha uma operação (1/2/3/4): ")
        
        if choice in ['1', '2', '3', '4']:
            num1 = float(input("Digite o primeiro número: "))
            num2 = float(input("Digite o segundo número: "))
            
            if choice == '1':
                print(f"Resultado: {num1} + {num2} = {add(num1, num2)}")
            elif choice == '2':
                print(f"Resultado:
