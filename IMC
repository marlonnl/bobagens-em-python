def calcularIMC():
    peso = float(input("Para iniciarmos, digite o seu peso (em kg): \n"))
    altura = float(input("Ótimo, agora digite a sua altura (em m): \n"))
    IMC = round(peso / altura ** 2,2)
    condicao = IMCstatus(IMC)
    
    print(f"Seu IMC é de {IMC}. Isso quer dizer que você está {condicao}.")

def IMCstatus(x):
    x = float(x)
    if x <= 18.5: return "magro(a)"
    if x > 18.5 and x < 24.9: return "no peso ideal"
    if x > 25 and x < 29.9: return "com sobrepeso (grau I)"
    if x > 30 and x < 39.9: return "com sobrepeso (grau II)"
    if x > 40: return "com sobrepeso (grau III)"
    
def selecionar(opcao):
    if opcao == 1:
        calcularIMC()
        #salvar = input("Deseja salvar o resultado? (S/N) \n")
        #if salvar = "S": salvar()
        
    if opcao == 2:
        historico()

print("Bem vindo a calculadora de IMC. \nO que você deseja fazer? \n(1) Calcular meu IMC; \n(2) Verificar histórico.")
a = int(input(""))
selecionar(a)
