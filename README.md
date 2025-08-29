# Figures
---
This is a lab for Vanier's Programming 1 course.

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

**A:** By invoking *movehorizontal(-70)*.