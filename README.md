- 👋 Hi, I’m @198299
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
198299/198299 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
1) Programa 1 - Programa que lê um conjunto de valores reais digitados pelo usuário e identifica o maior e o menor encontrados, bem como contabiliza a quantidade de números digitados e calcula a média destes valores. O programa deve encerrar quando o usuário digitar a palavra "Termino"

N=input(" Entre com um numero Real --> ")

maior=menor=N

cont,soma=1,N


while True :

if N > maior :

maior = N

elif N < menor :

menor = N

N=input(" Entre com um numero Real -->")

cont = cont + 1
 

print ( " O maior Valor é {:.2f}". format( maior))

print ( " O menor Valor é {:.2f}". format( menor))

print ( " O numero de valores digitados é {:.2f}". format( cont))

print ( " A media dos valores digitados é {:.2f}". format(soma/cont))
