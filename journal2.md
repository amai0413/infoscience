#This is a journal for Computer Science.

#What we did for class. We learned about the probability.

#What did you learned during class? I learned new easy grammer.

def setup(): 
 size(600,600)
 background(255)
 strokeWeight(30)

def draw(): 
    stroke(0)
    
def mouseClicked():
    stroke(0) #red,green,blue
    rect(100,100,400,400,50)
    stroke(255,0,0)  #red,green,blue
    n = random(0,7)
    
    if 0<=n<2:
        circle(300,300,50) #center
        
    if 2<=n<3:
        circle(400,200,50) #top right
        circle(200,400,50) #bottom left
        
    if 3<=n<4:
        circle(400,200,50) #top right
        circle(300,300,50) #center
        circle(200,400,50) #bottom left
        
    if 4<=n<5:
        circle(400,200,50) #top right
        circle(400,400,50) #bottom right
        circle(200,200,50) #top left
        circle(200,400,50) #bottom left
        
    if 5<=n<6:
        circle(400,200,50) #top right
        circle(400,400,50) #bottom right
        circle(300,300,50) #center
        circle(200,200,50) #top left
        circle(200,400,50) #bottom left
        
    if 6<=n<7:
        circle(200,200,50) #top left
        circle(200,300,50) #middle left
        circle(200,400,50) #bottom left
        circle(400,200,50) #top right
        circle(400,300,50) #middle right
        circle(400,400,50) #bottom right
        
        
        
