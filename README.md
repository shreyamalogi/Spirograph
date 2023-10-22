# Spirograph 🌀

🌈 Welcome to the Begginer-friendly Spirograph Drawing project

Crafted and taught by **Shreya Malogi!** 🌐



[![GitHub stars](https://img.shields.io/github/stars/shreyamalogi/spirograph.svg?style=social)](https://github.com/shreyamalogi/spirograph/stargazers)

### Project Details: 🎨🐢📅✍️

- **Functionality:** Creates vibrant and mesmerizing spirograph drawings using Python's Turtle module.
- **Tech Stack:** `Python`, `turtle`, `random`
- **Author:** [@shreyamalogi](https://github.com/shreyamalogi/)
- **Year of Project:** 2021

---

# Table of Contents 📚

1. [Introduction](#introduction-)
2. [Prerequisites](#prerequisites-%EF%B8%8F)
3. [Installation](#installation-)
4. [Running the Script](#running-the-script-%EF%B8%8F)
5. [Understanding the Code](#understanding-the-code-)
6. [Customizing Your Spirograph](#customizing-your-spirograph-)
7. [Contribution](#contribution--show-your-support-star-this-)
8. [License](#license-%EF%B8%8F)

## Introduction 🎨

Welcome to Spirograph Drawing! This Python script allows you to create vibrant and mesmerizing spirograph drawings using the Turtle module. Get ready to unleash your creativity with a few lines of code! 🌀🌈

## Prerequisites 🛠️

Before you dive into the world of spirographs, make sure you have Python installed on your machine. If not, you can download it [here](https://www.python.org/downloads/).

## Installation 🐢

No additional modules are required for this script. Just make sure you have Python installed.

## Running the Script ▶️

1. Open the script in your favorite Python environment.
2. Run the script. This will launch the Turtle graphics window.

## Understanding the Code 🤓

Let's break down the provided Python code for the Spirograph Drawing script:

```python
import turtle as t
import random

myrtle = t.Turtle()
t.colormode(255)

def random_color():
    r = random.randint(0, 255)
    g = random.randint(0, 255)
    b = random.randint(0, 255)
    color = (r, g, b)
    return color

def draw_spirograph(size_of_gap):
    for _ in range(int(360 / size_of_gap)):
        myrtle.color(random_color())
        myrtle.circle(100)
        myrtle.setheading(myrtle.heading() + size_of_gap)

draw_spirograph(5)
```

### Code Explanation:

1. **Importing Libraries:**
   ```python
   import turtle as t
   import random
   ```
   - `turtle` is a module in Python that provides a way to create simple graphics.
   - `random` is a module that provides functions for generating random numbers.

2. **Creating a Turtle:**
   ```python
   myrtle = t.Turtle()
   t.colormode(255)
   ```
   - `myrtle` is an instance of the `Turtle` class, which is used for drawing.
   - `t.colormode(255)` sets the color mode to use RGB values ranging from 0 to 255.

3. **Generating Random Colors:**
   ```python
   def random_color():
       r = random.randint(0, 255)
       g = random.randint(0, 255)
       b = random.randint(0, 255)
       color = (r, g, b)
       return color
   ```
   - The `random_color` function generates a random RGB color and returns it as a tuple.

4. **Drawing Spirograph:**
   ```python
   def draw_spirograph(size_of_gap):
       for _ in range(int(360 / size_of_gap)):
           myrtle.color(random_color())
           myrtle.circle(100)
           myrtle.setheading(myrtle.heading() + size_of_gap)
   ```
   - The `draw_spirograph` function uses a loop to draw circles in a spirograph pattern.
   - `myrtle.color(random_color())` sets the turtle's color to a random color.
   - `myrtle.circle(100)` draws a circle with a radius of 100 units.
   - `myrtle.setheading(myrtle.heading() + size_of_gap)` changes the heading of the turtle, creating the spirograph effect.

5. **Executing the Drawing:**
   ```python
   draw_spirograph(5)
   ```
   - This line calls the `draw_spirograph` function with a `size_of_gap` of 5, determining the gap between each circle in the spirograph.

The script, when executed, will create a visually appealing spirograph drawing with randomized colors. Adjusting the parameters can lead to various spirograph patterns.
## Customizing Your Spirograph 🎨

Feel free to experiment with the script! Adjust the `size_of_gap` parameter in the `draw_spirograph` function to change the gap between each circle in the spirograph. You can also modify colors, circle radii, and other parameters to create various spirograph patterns.

## Contribution- Show Your Support (Star This) ⭐🌟📜✨

Enjoying the magic of spirographs? Contribute to this creative journey and make it even more enchanting. Don't forget to star the project! ⭐🌟

## License ⚖️

This project is enchanted under the spell of the MIT License. Share the magic responsibly!

**MIT License**

Copyright (c) 2021 Shreya Malogi

Stay Enchanted! 🌍💙
