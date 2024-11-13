### Project during OBJECT ORIENTED METHODOLOGY course

**Topic** - Applet Communication		     

**Languages Used** - Java(AWT + Swing)

---

##### Members - 

1. Anirudh Korturti
2. Aryan Raj
___

#### Introduction:

The project asks us to show communication between two applets. An applet is a program that works on a web page using HTML link. I made this as a part of OOM Mini Project!
___

#### Motivation:

This project was a way to explore the application of Object Oriented approach in Graphical User Environment, and also to explore the applets through Java language.
___

#### Project Description:

The project is implemented in two instances: **Core AWT** and **AWT + Swing**.
The AWT instance works via **appletviewer**, while the Swing instance works via Java **NetBeans**.

In this project we have, created two applets, EnterShapeApplet and ShapeColorApplet.  These applets are made to communicate with each other.
The first applet EnterShapeApplet takes in the dimensions of the shape and allows us to pick a color. The second applet shows the shapes which we have given as input. The shapes in the second applet undergo a transition from one shape to another shape and the color of the shapes is the one we selected in first applet.

The transition of the shapes is done in an separate thread(so as to prevent the transition function to block the main thread). This is done using java.util.Timer .

After we run the program, the two applets open and the first applet takes input and the second applet shows the transition of the shapes.
___

#### Procedure to Run:

1. Enter the RGB valid values(in AWT instance), or select color from ColorChooser (in Swing instance).
2. Select size of the shapes(if entered none, default value is 10);
3. Press ‘Start’ button.
4. Transition of shapes start in the second applet, which shows three shapes, Rectangle, Triangle and Circle, in an interval of 1 second.
5. Press ‘Stop’ button in first applet to stop the transition in the second applet.


---
