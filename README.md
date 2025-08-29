# Figures
---
This is a lab for Vanier's Programming 1 course.

## Part 3
### Answers:

**Q: What happens if you call *moveDown* twice?**  

**A:** Everytime moveDown() is called the object moves down 20 pixels:
``` java
public void moveDown()
    {
        moveVertical(20);
    }
```

**Q: What happend if you call *makeInvisible* twice?**  

**A:** If the object is visible is will disapear, if it is invisible, nothing will happens. So, if *makeInvisible* is called twice, the first time the figure will stay unchanged or disapear, the second time the figure will remain unchanged (invisible).


**Q: How can you use *move horizontal* to move the circle 70 pixels to the left?**  

**A:** By calling *movehorizontal(-70)*.  

**Q: What happens when you specify a color that is not known?**  
**A:** The figure becomes black.  

**Q: What happens when you call *ChangeColor()* without the quotes?**  
**A:** It returns the following error:
``` text
Error: cannot find symbol
```  

### Drawing

**Steps to create the drawing num.2:**

1. Create a circle and label is "Ground"
2. Make *Ground* visible using 
``` java 
Ground.makeVisible();
```
3. Make *Ground* green using  
``` java 
Ground.changeColor("green");
```
4. increase the size of *Ground* using
``` java
Ground.changeSize(1000);
```
5. Recenter *Ground* using
``` java
Ground.moveHorizontal(-500);
Ground.moveVertical(120);
```
6. Create to people called "personBig" and "personSmall"
7. Make both black using the changeColor() method.
8. Make both visible using the makeVisible() method.
9. Make *personBig* bigger using
``` java 
personBig.changeSize(100, 60);
```
10. Move *personBig* to the left by 60 pixels using:
``` java
personBig.moveHorizontal(-60);
```
11. Move *personBig* vertically using:
``` java
personBig.moveVertical(-50);
```
12. Move *personSmall* vertically using:
``` java
personSmall.moveVertical(-20);
```
13. Create a circle called "Sun"
14. Make it visible.
15. Make it yellow using the changeColor method.
16. Move it to the right using
``` java
Sun.moveHorizontal(100);
```
![Drawing 02] (img/Drawing2.png)







