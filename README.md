import turtle
import time
turtle.setup(700, 700)

win = turtle.Screen()

win.title("Shape factory")

t = turtle.Turtle()

t.speed(0)

turtle.bgcolor("Black")

while True:

    ps = int(input("what pensize do you want?"))

    t.pensize(ps)

    cl = input("What color do u want? ").strip()
    time.sleep(1)

    t.pencolor(cl)

    sid = int(input("How much sides? "))
    time.sleep(1)

    k = int(input("How much degrees in angle? "))
    time.sleep(1)

    for x in range(sid):
        t.rt(k)
        t.fd(100)



    if False:
        turtle.done()
