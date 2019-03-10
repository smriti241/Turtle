# Turtle
import turtle
def square():
    window = turtle.Screen()
    window.bgcolor("yellow")
    move = turtle.Turtle()
    move.shape("circle")
    move.color("red")
    move.speed(5)
    move.forward(100)
    for i in range(3):
        move.right(90)
        move.forward(100)
    window.exitonclick()

square()
