avp1 = float(input("Digite a nota da AVP1: "))
avp2 = float(input("Digite a nota da AVP2: "))
TDE1 = float(input("Digite a nota do TDE1: "))
TDE2 = float(input("Digite a nota do TDE2: "))
TDE3 = float(input("Digite a nota do TDE3: "))
TDE4 = float(input("Digite a nota do TDE4: "))

media = (0.4 * avp1) + (0.4 * avp2) +(0.05 * (TDE1 + TDE2 + TDE3 + TDE4))

print("A média do aluno é: ", media)

if media >= 7:
  print("Aprovado")

elif media >= 4:
  print("Recuperação")

else: 
  print("Reprovado")
