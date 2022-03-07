from turtle import Turtle, Screen

import random

screen = Screen()
t = Turtle()


directions = [0, 90, 180, 270]
color_list = ["black"]


def random_color():
    r = random.choice(color_list)
    random_color_p = (r)
    return random_color_p

t.hideturtle()
t.pensize(1)
t.speed("fastest")

for _ in range(10000000):
    t.color(random_color())
    t.forward(7)
    t.setheading(random.choice(directions))



![random_walk_10](https://user-images.githubusercontent.com/100161430/157100174-a8754351-4d46-4829-aa91-48eb01f1f868.png)

![random_walk_8](https://user-images.githubusercontent.com/100161430/157100209-dfc3aad6-4e87-4bd4-9845-275e57d80919.png)

<img src="https://user-images.githubusercontent.com/100161430/156935226-f0b7114d-d93c-4f39-a0f3-82028f44bdcb.png">

![random_walk_4](https://user-images.githubusercontent.com/100161430/156936336-ebb2ad93-1870-4f18-96be-3870f2bf55a6.png)

![random_walk](https://user-images.githubusercontent.com/100161430/156937536-dc37d24e-8ed8-4d0c-b314-4e50da08cf0a.png)

