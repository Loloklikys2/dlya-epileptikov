# dlya-epileptikov
x1 = 1100
x2 = 1100
def setup():
    size(800,600)
    
def draw():
    global x1
    global x2
    fill(random(0,255),random(0,255),random(0,255))
    ellipse(400,300,x1,x2)
    x1 = x1 - 1
    x2 = x2 - 1
