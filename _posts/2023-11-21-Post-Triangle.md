---
layout: posts
title: Triangle Fracral
---
* ![Photo](\assets\images\triangle.png)
* [MyTree](C:\git\personal_website_template\static_files\triangleme.html)

<html>
<body>
<br>
<h4 style="text-align:right ;font-family: Tahoma">
   و تابع بازگشتی فرکتال مثلث را رسم کردیمturtleبا کمک کتابخانه
</h4>
<h3 style="text-align: right;font-family: Tahoma; color:rgba(249, 2, 35, 0.686)">در پایین میتوانید دستورات انرا ببینید</h3>
<pre>import turtle
    import random
    def triangle(d):
        turtle.pencolor(random.random(),random.random(),random.random())
        turtle.pensize(1.4)
        
        if d < 5:
            return    
        for _ in range(3):
            triangle(d/2)
            turtle.forward(d)
            turtle.left(120)
    turtle.penup()
    turtle.backward(200)
    turtle.pendown()
    turtle.bgcolor("black")
    turtle.tracer(0)
    turtle.speed(0)
    triangle(300)
    turtle.update()
    turtle.mainloop()
    </pre>
</body>
</html>