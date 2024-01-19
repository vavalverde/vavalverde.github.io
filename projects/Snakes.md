---
layout: project
type: project
image: img/Snake.png 
title: "Snakes Like Apples"
date: 2020
published: true
labels:
  - Java
  - Eclipse
summary: "I made a simple fun game to play to explore the capabilities of Java."
---

<div class="text-center p-4">
  <img width="300px" src="../img/End.png" class="img-thumbnail" >
  <img width="300px" src="../img/Color.png" class="img-thumbnail" >

</div>


Welcome to the sophisticated world of the Snake Game, a captivating and elegantly designed project crafted using Java in Eclipse. This project showcases not only the classic Snake Game mechanics but also incorporates advanced features, polished user interface, and efficient code architecture.

The Snake Game is a timeless classic, and our project aims to elevate this simplicity to sophistication. The game revolves around a snake that grows longer as it consumes food items, with the challenge lying in avoiding collisions with walls and the snake's own tail. However, our rendition goes beyond the conventional and introduces elements that redefine the gaming experience.

   The game boasts a sleek and modern user interface that engages players from the moment they launch the application. The carefully chosen color palette, intuitive layout, and smooth animations contribute to a visually appealing experience. Our Snake Game is not confined to a fixed window size. It adapts seamlessly to various screen resolutions, ensuring an optimal gaming experience across different devices. Whether you're playing on a desktop or a laptop, the game adjusts its layout for maximum enjoyment.

(I was unable to take a screenshot of the game when it reaches the rainbow levels because I am not very good)
```cvv
public void checkCollisions() {
		//checks if head collides with body
		for(int i = bodyParts;i>0;i--) {
			if((x[0] == x[i])&& (y[0] == y[i])) {
				running = false;
			}
		}
		//check if head touches left border
		if(x[0] < 0) {
			running = false;
		}
		//check if head touches right border
		if(x[0] > SCREEN_WIDTH) {
			running = false;
		}
		//check if head touches top border
		if(y[0] < 0) {
			running = false;
		}
		//check if head touches bottom border
		if(y[0] > SCREEN_HEIGHT) {
			running = false;
		}
		
		if(!running) {
			timer.stop();
		}
	}
```
