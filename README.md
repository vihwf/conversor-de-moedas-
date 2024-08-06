# conversor-de-moedas-
Digite um valor em real para transformar em dolar 
din = float(input('Quanto de dinheiro você tem na carteira? R$'))
dolar = din / 5.66
print('Com R${} você pode comprar US${:.2f}'.format(din, dolar))
