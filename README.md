#This is a journal for Computer Science.

#What we did for class.
We learned how to use Python and Processing.

#What did you learned during class?
I learned how to code a program in Python.

def setup():
 size(1000, 1000)
 background(255)
 textAlign (CENTER)

def mouseClicked():
    x = mouseX
    y = mouseY
    r = random(50,90)
    myred = random(0,255)
    mygreen = random(0,255)
    myblue = random(0,255)
    fill(myred,mygreen,myblue)
    
    circle (x,y,r)
    fill  (0)
    textSize (0.5*r)
    text ("Ai",x,y)

    print(x,y)
    
def draw():
    v=0
    
    #HomeWork Second class
    1.Add lines from the middle of the window to ezch circle.
    2.Add lines from circle to circle.
