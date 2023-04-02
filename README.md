# BIKIN BUNGA DI PYTHON

```py
# bikin bunga menggunakan pyhon
import turtle

t = turtle.Turtle()
s = turtle.Screen()

s.bgcolor('black')
t.speed(0)
col = ("yellow", "red", "pink", "cyan", "light green", "blue")
for i in range (150):
    t.pencolor(col[i%6])
    t.circle(190-i/2,90)
    t.lt(90)
    t.circle(190-i/3,90)
    t.lt(60)

s.exitonclick()
```

output : 

![image](https://user-images.githubusercontent.com/92344349/229367348-4c6f9c40-5bab-4e9d-a144-e093fc243dec.png)

# SPIRAL PYTHON

```py
import turtle

# membuat layar turtle
screen = turtle.Screen()
screen.bgcolor("black")

# membuat turtle
pen = turtle.Turtle()
pen.speed(0)
pen.color("white")

# membuat spiral
for i in range(100):
    pen.forward(i * 5)
    pen.right(144)

# menutup layar setelah di-klik
screen.exitonclick()

```

![image](https://user-images.githubusercontent.com/92344349/229380087-3a02e521-fc23-4bb1-9f16-46d83ff8eca3.png)

# TAMENG CAPT AMERIKA 

```py
import turtle

# membuat layar turtle
screen = turtle.Screen()
screen.bgcolor("black")

# membuat turtle
pen = turtle.Turtle()
pen.speed(0)

# menggambar lingkaran bagian luar
pen.color("red")
pen.begin_fill()
pen.penup()
pen.goto(0, -250)
pen.pendown()
pen.circle(250)
pen.end_fill()

# menggambar lingkaran bagian dalam
pen.color("white")
pen.begin_fill()
pen.penup()
pen.goto(0, -200)
pen.pendown()
pen.circle(200)
pen.end_fill()

# menggambar lingkaran kecil di tengah
pen.color("blue")
pen.begin_fill()
pen.penup()
pen.goto(0, -100)
pen.pendown()
pen.circle(100)
pen.end_fill()

# menggambar bintang di lingkaran biru
pen.color("white")
pen.penup()
pen.goto(0, 20)
pen.pendown()
pen.begin_fill()
for i in range(5):
    pen.forward(60)
    pen.right(144)
pen.end_fill()

# menutup layar setelah di-klik
screen.exitonclick()

```

output

![image](https://user-images.githubusercontent.com/92344349/229380414-7fabcbfa-1f23-49c3-af09-80047d707a59.png)


