# ASnakesAdventure
 My attempt at "A Snake's Adventure" Computer Vision challenge on data-puzzels.com. 

Found here : https://data-puzzles.com/challenges/follow-the-snake/

The goal is to find out the snakes name using the large folder of images.

The images vary and look as such :

![EX1](https://github.com/geobrignell/ASnakesAdventure/assets/89096835/d73a6784-0a34-4742-b739-37a21c39ff0e)
![EX2](https://github.com/geobrignell/ASnakesAdventure/assets/89096835/856dad2d-0b6b-486a-8543-3d74517b4d39)

The challenge also gives you : 

![focus](https://github.com/geobrignell/ASnakesAdventure/assets/89096835/2642910c-e288-4076-8dd3-42e99be0330b)

You need to use this clue.

For each image you need to find the location of the snake, and match it to its direction on the clue.

This leads to a large array of directions which were then used to draw out the snakes name in order to get the answer for the challenge.

![answer](https://github.com/geobrignell/ASnakesAdventure/assets/89096835/1ea30eca-daff-4f57-94de-9efa10fbe358)

I used OpenCVs matchTemplate function to complete this challenge.
