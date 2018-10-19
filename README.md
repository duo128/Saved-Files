# Saved-Files
x=-200

def setup():
    size(640,480)

def draw():
    global x
    if x>=700:
        x=-200
    x+=0.5
    background(135,206,250)
    
    noStroke()
    fill(255,255,0)
    ellipse(620, height/12,200,200)
    
    fill(255,255,255)
    ellipse(x, height/3, 70, 70)
    ellipse(x + 50, height/3, 70,70)
    ellipse(x + 100, height/3,70,70)
    ellipse(x + 25, height/3.8,70,70)
    ellipse(x + 75, height/3.8,70,70)
    ellipse(x + 50, height/4.2,70,70)
    
    noStroke()
    fill(100)
    triangle(0,640,200,200,400,640)

            
    
