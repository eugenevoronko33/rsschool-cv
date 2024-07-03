# CV for RSSchool 

## Eugene Voronko - Beginner Webmaster 
![Profile image](https://stihi.ru/photos/3redstar3.jpg?8169)

# Contacts 


**Email:** eugene.voronko.33@gmail.com   
**Phone:** +375 33 6892753   
**Address:**  city Grodno , Belarus  
**LinkedIn:** [https://www.linkedin.com/in/eugene-voronko-8806001aa/](https://www.linkedin.com/in/ivanivanov)  
**GitHub:** [https://github.com/eugenevoronko33](https://github.com/eugenevoronko33)  

---

## Education

**Yanka Kupala Grodno State University**, Grodno, Belarus  
*Master of Computer Science*   
September 2020 - January 2022  

**Yanka Kupala Grodno State University**, Grodno , Belarus 
*Bachelor's Degree in Information Technology Software*   
September 2016 - June 2020 

---

## Work experience

**LLC "* instinctools"**, Grodno, Belarus 
*Beginner web developer*  
December 2018 - March 2019 

- Development and support of web applications using JavaScript,SQL, NOSQL 
- Implementing a micro-service architecture for scalable solutions 

**CHUP "Айтишник"**, Grodno, Belarus 
*System Administrator*   
October 2023 - Present   

- Support and configuration of network and office equipment 
- Training of novice administrators 
- Conducting equipment testing 

**CHUP "Айтишник"**, Grodno, Belarus 
*Consultant*   
October 2022 - October 2023   

- Teaching IT technology to students  
- Advising beginners in choosing a direction 


**Yanka Kupala Grodno State University**, Grodno, Belarus 
*Teacher*   
January 2023 - Present   

- Training of students in the field of information systems administration 
- Develop your own training plan in the field of administration 

---
## Skills 

- Programming languages: Python, JavaScript, SQL, PHP, C#  , Kotlin, Android Java  
- Web technologies: HTML, CSS, React, Angular, NodeJS 
- Tools and technologies: Git, Docker  
- Databases: PostgreSQL, MySQL, MongoDB  
- Software development methods: Agile, Scrum  
- OS: Windows , Ubuntu , CentOS , Linux Mint and other  

## Projects 

**Personal page game group**  

*Description:*    Development of a personal page for a gaming group   
*Role:* Developer    
*Technology:* HTML, CSS, JavaScript, MongoDB, React   

**Messanger**  

*Description:* Creating a mobile application to communicate with friends   
*Role:* Developer   
*Technology:*  Kotlin, Firebase , Android  

---

## Code example 
```python

ef snake_move():
    if snake.direction == "up":
        y = snake.ycor()
        snake.sety(y + 20)

    if snake.direction == "down":
        y = snake.ycor()
        snake.sety(y - 20)

    if snake.direction == "left":
        x = snake.xcor()
        snake.setx(x - 20)

    if snake.direction == "right":
        x = snake.xcor()
        snake.setx(x + 20)


def snake_go_down():
    if snake.direction != "up":
        snake.direction = "down"

def snake_go_up():
    if snake.direction != "down":
        snake.direction = "up"

def snake_go_right():
    if snake.direction != "left":
        snake.direction = "right"

def snake_go_left():
    if snake.direction != "right":
        snake.direction = "left"
screen.listen()
screen.onkeypress(snake_go_down, "Down")
screen.onkeypress(snake_go_up, "Up")
screen.onkeypress(snake_go_left, "Left")
screen.onkeypress(snake_go_right, "Right")
while True:
    screen.update()
    if snake.distance(fruit) < 20:
        x = random.randint(-290, 270)
        y = random.randint(-240, 240)
        fruit.goto(x, y)
        scoring.clear()
        score += 1
        scoring.write("Счет:{}", format(score), align="center", font=("Courier", 24, "bold"))
        delay -= 0.001
        new_fruit = turtle.Turtle()
        new_fruit.speed(0)
        new_fruit.shape('square')
        new_fruit.color("red")
        new_fruit.penup()
        tail.append(new_fruit)
        for index in range(len(tail) - 1, 0, -1):
            a = tail[index - 1].xcor()
            b = tail[index - 1].ycor()
            tail[index].goto(a, b)
        if len(tail) > 0:
            a = snake.xcor()
            b = snake.ycor()
            tail[0].goto(a, b)
        snake_move()
        if snake.xcor() > 280 or snake.xcor() < - 300 or snake.ycor() > 240 or snake.ycor() > -240:
            time.sleep(1)
            screen.clear()
            screen.bgcolor("turquoise")
            scoring.goto(0, 0)
            scoring.write(" GAME OVER \n Ваш Счет {}", format(score), align="center", font=("Courier", 30, "bold"))

        for part in tail:
           if part.distance(snake) < 20:
               time.sleep(1)
               screen.clear()
               screen.bgcolor("turquoise")
               scoring.goto(0, 0)
               scoring.write(" GAME OVER \n Ваш Счет {}", format(score), align="center", font=("Courier", 30, "bold"))

        time.sleep(delay)

```


## Languages 

- Russian (native) 
- English (advanced - reading) 

---

## Personal qualities 

- Excellent communication skills  
- Ability to work in a team and independently  
- High adaptability to changes  

---

## Interests 

- Artificial intelligence and machine learning  
- Open-source projects  
- Reading science fiction  
- Cars   
- Operating systems  
- Implementation of microservices  

<img src="img\rs_school_js.svg" width="200" height="200"> 
