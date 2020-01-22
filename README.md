# Oscillating Rhodonea
This repository contains a creative refactoring of Dan Shiffman's Coding Challenge: Mathematical Rose Patterns. It combines the concepts of polar coordinates, covered in Shiffman's video, and oscillations. 

You can view the Oscillating Rhodonea Web Environment [here](https://sabrinabutton.github.io/oscillating-rhodonea/)!

## Note
In this refactoring, the denominator K is calculated by dividing a numerator by a denominator. The value of the denominator oscillates. This oscillation, dealing with very precise values, makes it hard to utilize the initial reduceDenominator function as it can never reduce the numbers enough to be able to have a remainder of zero without creating an absurdly large number. This is an issue because roses are drawn either too many times or not enough, and an odd-looking horizontal line appears. A way to tackle this was to round the denominator to two decimal places or make the number an integer. I tried this, and it worked, but I felt that it took away from the visual experience of the oscillation, as the rose didn't appear to be animated but rather appeared to be a slideshow. So I decided to sacrifice perfection of the app for something that looks cool - sue me.  

## Links 
- [Coding Train Coding Challenge: Mathematical Rose Patterns](https://thecodingtrain.com/CodingChallenges/055-roses.html)
- [The AYJACKSON_ICS4U Repo Containing This Code](https://github.com/AYJACKSON-ICS4U/mathematical-rose-patterns-refactors/tree/master/sabrina)
