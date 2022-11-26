# L0: ASCII Art

This first lab is designed to help us learn to use our tools and to program in C++.

## Starter files have been provided for you in C++

### Author:
- Author of modified ASCII art program: Dimitrios Ntentia

# Planning Prompts
## Due at Milestone 1

1. **ART CHOICE**
*Go to [Christopher Johnson's ASCII Art Collection ](https://asciiart.website/) and find a piece of ASCII art that you would like to modify and render in C++ using cout.  What did you find? Please note that it is fine either to modify it only a little or quite significantly. Put the URL here AND also in a comment in your code or state that your art is original in both places.*

https://asciiart.website/index.php?art=objects/buildings

/*                           (   )
                          (    )
                           (    )
                          (    )
                            )  )
                           (  (                  /\
                            (_)                 /  \  /\
                    ________[_]________      /\/    \/  \
           /\      /\        ______    \    /   /\/\  /\/\
          /  \    //_\       \    /\    \  /\/\/    \/    \
   /\    / /\/\  //___\       \__/  \    \/
  /  \  /\/    \//_____\       \ |[]|     \
 /\/\/\/       //_______\       \|__|      \
/      \      /XXXXXXXXXX\                  \
        \    /_I_II  I__I_\__________________\
               I_I|  I__I_____[]_|_[]_____I
               I_II  I__I_____[]_|_[]_____I
               I II__I  I     XXXXXXX     I
            ~~~~~"   "~~~~~~~~~~~~~~~~~~~~~~~~

*/

2. **REASON FOR ART CHOICE**


I like this picture because it is a very common set I used to create when I was younger in elementary school


3. **USER INPUT**
*It is required that you incorporate input from the user, but this need not make you crazy. It can just be above or below your art if you want. It can also be put into a single character you print. Discuss how you plan to use the user’s input.*

I will ask the user to name the village the house belongs in and then I will print it in a sentence

4. **ESCAPE CHARACTERS**
<<<<<<< HEAD
I need to escape using the "" double quotation mark and the single quotation mark that exist in the above art piece. This is because they interfere with internal commands of the C language. Also when using a backslash, I will need to have a double backshlash
=======
<<<<<<< HEAD
I need to escape using the "" double quotation mark and the single quotation mark that exist in the above art piece. This is because they interfere with internal commands of the C language. Also when using a backslash, I will need to have a double backshlash
=======
I need to escape using the "" double quotation mark and the single quotation mark that exist in the above art piece. This is because they interfere with internal commands of the C language
>>>>>>> 234377bfc9704e1334a728934a023a8f567af90c
>>>>>>> 522a557276ad2617bd3968ca6a03989758679abf

*There is no meaningull spacing in C, therefore bot the spacing character needs to be adjusted. We can fix the spacing by using a cout << "LINE" << endl; format *

5. **PREPLAN**
*Later on in this course, we will focus more on developing a logical plan rather than fighting with syntax, but for this first lab, we need to conquer C++ syntax!  Write a bulleted list of your attack plan to achieve success on this lab.*
  - Identify art
  - Indentify packages
  - Figure out adjustments
  - Write the input and output

# Implementation & Customization Prompts
## Due at  Milestone 2

6. **TITLE**
The Fiddler on the Roof of a little house


7. **CUSTOMIZATIONS & MODIFICATIONS**
*What customizations and modifications did you ultimately make to the original art? (Remember that it is fine to modify it only a little or quite significantly.) Be sure to adjust your code comments to summarize your modifications. Remember  to save often and push your work up to Github. For a detailed workflow description on how to do this, see: [VS, Github, & ASCII art](https://drive.google.com/open?id=1Bz1sbwxid1ydkSHaO5nDMpMgzwa29Py6zzTlWGUvBzM)*.

<<<<<<< HEAD
I changed the way the smoke looked and made it thicket. I swapped the bottom double  quotation marks with [ ] instead and built a person on the roof. The double backslash also made me fix the mountain are, by subtracting several \
=======
<<<<<<< HEAD
I changed the way the smoke looked and made it thicket. I swapped the bottom double  quotation marks with [ ] instead and built a person on the roof. The double backslash also made me fix the mountain are, by subtracting several \
=======
I changed the way the smoke looked and made it thicket. I swapped the bottom double  quotation marks with [ ] instead and built a person on the roof
>>>>>>> 234377bfc9704e1334a728934a023a8f567af90c
>>>>>>> 522a557276ad2617bd3968ca6a03989758679abf

*FIXME*

/*                                                
                   ++ +++ + 
                    ++ +++ +         ____
                      ++ +++ +      (* * )
                        ++ +++ +      |   
                           ++ +++ + --|--(XXXXXXX)--X
                           ++ +++ +   |   
<<<<<<< HEAD
=======
<<<<<<< HEAD
>>>>>>> 522a557276ad2617bd3968ca6a03989758679abf
                             ++ +    / \\      /  \\  /\\
                    ________[_]________      /\\\/    \\/  \\
           /\\      /\\        ______    \\   /   /\\/\\  /\\\\
          /  \\    //_\\      \\     /\\  \\ /\\ /    \\\   \\
   /\\   / / /\\  //___\\      \\__ /  \\  \\
  /  \\ /\\    \\//_____\\      \\ |[]|     \\
 /    \\       //________\\      \\|__|      \\
/      \\     /XXXXXXXXXXx\\                   \\
        \\   /_I_II  I__I__\\________________  _\\
<<<<<<< HEAD
=======
=======
                             ++ +    / \      /  \  /\
                    ________[_]________      /\/    \/  \
           /\      /\        ______    \    /   /\/\  /\/\
          /  \    //_\       \    /\    \  /\/\/    \/    \
   /\    / /\/\  //___\       \__/  \    \/
  /  \  /\/    \//_____\       \ |[]|     \
 /\/\/\/       //_______\       \|__|      \
/      \      /XXXXXXXXXX\                  \
        \    /_I_II  I__I_\__________________\
>>>>>>> 234377bfc9704e1334a728934a023a8f567af90c
>>>>>>> 522a557276ad2617bd3968ca6a03989758679abf
               I_I|  I__I_____[]_|_[]_____I
               I_II  I__I_____[]_|_[]_____I
               I II__I  I     XXXXXXX     I
            ~~~~~]   [~~~~~~~~~~~~~~~~~~~~~~~~

*/





8. **PROCESS SUMMARY**
*Briefly summarize your design and implementation process,
including how much your initial design plan evolved,
the final results you achieved, and the amount of time you spent
as a programmer in accomplishing these results.
This should be one or at most two paragraphs.*

I used the main.ccp as my template when designing the program. Then I started working on chaning the art piece, which is when I realized \ cound not be used and I had to change some parts of it.

After I was done with the art piece, I wrote down a very small model of my program in python and then translated everything in C++. The planning process was less than 15 minutes. To do that I used at least 1 and a half hours because I was looking at book going back and forth










9. **DESIGN CHALLENGES**
*Describe the primary conceptual challenges that you encountered
in trying to complete this lab and what might have made the lab easier for you.*

I think that I mainly had some issues with the questions because I did not know how to respond to them, or where to look for answers. I would love it if the questions could some times redirect you to find the answers
in a resource or even an online resource


10. **ERRORS**
*List in bulleted form of all known errors
and deficiencies with a very brief explanation.*
- There should be no errors or items to debug. The code works on my version of visual studio, with no issues


11. **LEARNING AND REACTION**
I learned how important the punctuation is in C and that the debugger does not really help you with simple punctuation


# Update, Debug, and Integrity Statement
## Due at Final milestone

Note: All FIXME's should have been *fixed* at each milestone, so there should be none left after final submission.

12. **INTEGRITY STATEMENT**
I had no references, I used knowledge from the book and the data provided here
<<<<<<< HEAD

=======
>>>>>>> 522a557276ad2617bd3968ca6a03989758679abf
