#Quadrado
for _ in range(4): #Loop para repetição
    t.color("red") #Cor do quadrado
    t.forward(100) #Anda para frente
    t.left(90) #Gira para esquerda
   
#Triângulo Equilátero

t.penup() #Sobe a caneta
t.goto(0,150) #Posiciona a seta
t.pendown() #Abaixa a caneta
t.color("green") #Cor do triângulo
t.forward(100)#Anda para frente
t.left(120) #Gira para esquerda
t.forward(100)#Anda para frente
t.left(120) #Gira para esquerda
t.forward(100)#Anda para frente


#Circulo

t.penup()#Sobe a caneta
t.goto(5,355) #Posiciona a seta
t.pendown()#Abaixa a caneta
t.color("black") #Cor do circulo
t.circle(50) #Faz a circuferência 

#Heptágono

t.penup()#Sobe a caneta
t.goto(77,-150) #Posiciona a seta
t.pendown()#Abaixa a caneta
t.color("blue") #Cor do heptágono
t.setheading(180) #Direciona a seta
for _ in range (7):  #Loop para repetição
    t.forward(50) #Anda para frente
    t.right(51.50) #Gira para direita

#Losango

t.penup()#Sobe a caneta
t.goto(5,-280) #Posiciona a seta
t.pendown()#Abaixa a caneta
t.color("orange") #Cor do losango
t.left(120) #Gira para esquerda
t.forward(100) #Anda para frente
t.left(120) #Gira para esquerda
t.forward(100) #Anda para frente
t.left(60) #Gira para esquerda
t.forward(100) #Anda para frente
t.left(120) #Gira para esquerda
t.forward(100) #Anda para frente
