# An algorithm that I spun up to fix my box-shadow pixel art

I made the mistake of drawing pixel art with [Pixel Art to CSS](https://www.pixelartcss.com/) to generate CSS to create pixel art and now I face the consequences of my actions.

I finished drawing Ms. Muffet from UnderTale using the box-shadow property and `position: absolute` in CSS when I realized she was too far to the right.

When I attempted to use the left and right property to scoot her more to the left, I realized the div was already hitting the end of the webpage.

I realized I was doomed to redraw Ms. Muffet or manually change 300 lines of pixel values in the code. So, I converted all the RBGA values to a string and created an algorithm to move Ms. Muffet without having to move the div.

I used [NotePad++](https://notepad-plus-plus.org/) to remove the white space from CSS formatting.

Here is Ms Muffet!

![Ms-Muffet-Pixel-Art](/ms-muffet.png)
