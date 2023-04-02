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

