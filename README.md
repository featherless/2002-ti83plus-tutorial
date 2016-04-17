# TI83+ programming tutorial

> A chapter of featherless' [digital creative history](https://github.com/featherless/digital-creative-history).


    PLEASE MAXIMIZE THIS WINDOW!
    AND TURN ON WORDWRAP TOO!

                             _   _    ___    _   _   _     _______    ___
                            | | | |  / _ \  | | | | | |   |__   __|  /   \
                            | |_| | | / \ | | | | | | |      | |    | / \ |
                            |  _  | ||   || | |_| |_| |      | |    ||   ||
                            | | | | | \_/ | |         |      | |    | \_/ |
                            |_| |_|  \___/   \_______/       |_|     \___/

                                         Program on the TI83+
                                       \~--------------------~/

                                           Table of Contents
                                        \~------------------~/
                                         \                  /
                                          \                /
                                           \              /
                                            \            /
                                             \          /
                                              \        /
                                               \      /
                                                \    /
                                                 \  /
                                                  \/

                    Section 1..............Introduction
                    Section 2..............Getting Started (With programming)
                    Section 3..............The next level....
                    Section 4..............Time to CLEAR some things up!
                    Section 5..............While loops are just the same
                    Section 6..............Input and Output, not as confusing as they seem

                                        Section 1- Introduction
                                      \~-----------------------~/

                                               Welcome!
            First of all, I would like to thank you for even reading this README file in the
            first place, and I would also like to congratulate you because it could mean
            you'll end up going down the path of programming (for a lovely pay check of 80K+
            per year!).  When I first got my TI83+, it was only about the 2nd or 3rd time
            I'd ever even used it before (that was 1 year ago in 8th grade X-mas) and now
            I'm pretty much able to type on it like a keyboard, program anything I'd like,
            within the limits of the RAM on my calc of course, hehe.
            I remember that fateful day I got my TI83+ down to the point...lets see, I got
            the TI83+ from my mom as a present, and about 10 mins after opening the package
            to it, I had already read the first 3 chapters of the book it came with.
            "Well," I thought to myself as I got to Chapter 16 later that night, "I think I
            could really get to like this!" and within about 20 mins of reading Chapter 16,
            I had already made 3 programs: Volume of a Cylinder, Area of a Square, and
            Perimeter of a Square.  Now, I know, those aren't exactly the hardest programs
            to program, but little do some people know, there are hundreds of little
            shortcuts that you can use to make the program a lot smaller and smoother too!.
            Here is an example of one of the programs I made (copied from the book, because
            that's where I got it!)

            Oh, just a little sidenote, some of the symbols used on the calc I can't type
            in notepad, so bear with me, here's what the symbols below will mean on the calc....
                                    -->  The store button

                                    O~   The O with the line in the middle

                                    �    Negative sign (negative �  minus -)

                                    gte~ Greater Than or equal to sign

                                    lte~ Less than or equal to sign

                                    net~ Not Equal to sign

                    Also, there are some symbols used when it tells you the new commands used-

                            `name`   For Example-

                                    CTL I/O EXEC
                                    1:If
                                    2:Then
                                    3:Else
                                    4:....etc

                                    If it says 'CTL', then you need to go to the CTL menu and press
                                    whatever number needs to be pressed there to get that command.

                            *name*   For Example-
                                    On your calculator, there are many buttons, if you see a word
                                    with stars around it, that means that you need to press that
                                    button to access that menu.


    Now to the Program: Volume of a Cylinder, copied right from the Texas Instruments manual (no,
       I am not taking credit for it!)

                                    PROGRAM:CYLINDER
                                    :Prompt R,H
                                    :&#960;R�H-->V
                                    :Disp "VOLUME IS",V
                                    :

    That was the very first program I ever made for the calculator, and I was actually quite
    proud that I did it, even though it is only 3 lines of commands!  However, later on I will
    break it down to you and show you how it works, along with some ways to make the program
    smaller, yet still do the exact same thing!


                              Section 2- Getting Started (With Programming)
                            \~---------------------------------------------~/


            Now, hopefully you read the Introduction part of this readme already, or else you
            won't get much of what I'm saying due to font restrictions...but if you have, here
            you are, on section 2 of my wonderfully informative Programming Readme!
            OK, so, you want to start programming right?  You wanna get out there and make the
            next Final Fantasy or the next Zelda or the next Mario, or maybe you just want to
            make some programs that people can use, like word or excel....well, no can do!!
            Sorry to be blunt, but if this is your first time programming, you can forget about
            working for Nintendo or Microsoft right now, because you're gonna need to get a
            little experience under your wing first.  So, whip out your calculator right now,
            and follow my instructions, because these'll bring you one step closer to being a
            better programmer.

            First, I'd like to start with a little basic program using just the basic commands...

                                    PROGRAM:COUNT
                                    :0-->A
                                    :Lbl A
                                    :A+1-->A
                                    :Disp A
                                    :If A=50
                                    :Stop
                                    :Goto A

                            New commands used-
                                    Lbl   *Prgm*-`CTL`-9
                                    Disp  *Prgm*-`I/O`-3
                                    If    *Prgm*-`CTL`-Enter
                                    =     2nd-*MATH*-`TEST`-Enter
                                    Stop  *Prgm*-`CTL`-Alpha-F
                                    Goto  *Prgm*-`CTL`-0

            Now, let's break that down.

                    1) :0-->A       Now, this part right here is pretty simple, it just stores zero
                                    to the variable A.

                    2) :Lbl A       This just declares that this is, well, let's say a marker point
                                    in the program, which can be used later....

                    3) :A+1-->A     This is also another easy little command, this just adds one
                                    number to the variable A, and then stores it to the variable A,
                                    in a sense it's just counting up by one.

                    4) :Disp A      Here, the Variable A, which has just gotten one number added to
                                    it, is displayed on your homescreen.

                    5) :If A=50     Now, I know you don't want to sit there with your calculator
                       :Stop        counting up and up forever until eventually either your batteries
                                    die or the LCD just burns up into a ball of flame (probably the
                                    former, hehe)  So we put this little command in here to basically
                                    do this: it tells the calculator that if A equals 50, then stop
                                    counting up and stop the program right there where it says Stop.

                    6) :Goto A      Remember that Lbl A command you typed in just a few command lines
                                    earlier?  Well, this Goto command is what you use to go back up
                                    to it.  Whenever you use the Goto command, you need to type in a
                                    letter right after it saying which Lbl you'd like it to go to (A
                                    in this case, but you can also use variables from AA to ZZ and 00
                                    to 99 and even A0 to Z9 or whatever you please, so there are
                                    roughly 1306 different labels you can have in one program).

                    7)              Now that you have finished typing up your program and I have
                                    finished breaking it down, here's the overall effect of the
                                    program and what it's doing-

                                    EXEC EDIT NEW
                                    1:COUNT

                                    ---Make sure EXEC is highlighted---

                                    ---Press Enter when COUNT is highlighted---
                                    prgmCOUNT

                                    ---Press Enter---
                                    prgmCOUNT
                                                   1
                                                   2
                                                   3
                                                   4

                                    ---And so on until it reaches 50, at which point it will stop---
                                                  49
                                                  50
                                                Done

            Ok, so now you've programmed your very first program that isn't from the book.  Just to
            let you know, as of this point in time, every program you see below this text(and the
            one right above) will be programs made by me and NOT copied from anyone else.

            So, what do you think?  Proud of yourself now that you've figured out the basics of the
            calculator's BASIC language?  Well, don't run off just yet and try to make some new
            version of Pac Man, you only know the basics, and there's a lot more to learn!


                                        Section 3- The next level....
                                      \~-----------------------------~/


            Now that you've made your first program, it's time to learn some more stuff.  In this
            next program, I will introduce you to the For( command and the End command.  With these
            two commands, you can end up saving a lot of space in your programs (in Raging Flame,
            the original versions V1.0 through V1.4 took up a lot more space than they needed to,
            and in the New Raging Flame, it takes up about half the space the other Raging Flame
            took up, and there's a lot more in it too!)

            Ok, you're going to recognize this program, it's the exact same one as above, except it
            uses the For( and End commands this time.

                                    PROGRAM:COUNT2
                                    :For(A,1,50
                                    :Disp A
                                    :End

                            New commands used-
                                    For  *Prgm*-`CTL`-4
                                    End  *Prgm*-`CTL`-7

            Now it's time to break it down again.....

                    1) :For(A,1,50  You will notice here that I didn't close the parenthesis on the
                                    For( command, this is NOT neccessary to do.  The only thing that
                                    the closing parenthesis does (I think at least) is take up one
                                    byte of your program that could be going to something else.  But
                                    anyways, this new command is a savior to all BASIC programmers.
                                    As you can see, this program takes up only 3 lines, while the
                                    other program takes up 7, and this program takes up only 26
                                    bytes, while the other one takes up 40 (that's 35% smaller than
                                    the other program! remember, the name of the program takes up
                                    space too, so I just took one bite off for the extra letter in
                                    the name.).  The For( command is not only a great space saver,
                                    but it's easy to use also, first of all, right after you type in
                                    your For( command, you need to tell it which variable you would
                                    like to use for the next few numbers, then you type a comma after
                                    it and the next two numbers (also separated by commas) tell the
                                    For( command what number to start at and what number to stop at.

                    2) :Disp A      Ok, you've seen this command before, so I'm not going to bother
                                    explaining it again.

                    3) :End         Here's the other new command, the End command.  This command is
                                    essential to your For( command so that it can run, if you forget
                                    your End command, nothing's gonna happen with your For( loop,
                                    it'll execute it once, and then it's done.

                    4)              Ok, so you've finished program number two now.  Here is what's
                                    happening when you run this program.  First, the For( loop is
                                    started, and it automatically stores whatever number you have
                                    right after (in this case 1) and then it adds one to that number
                                    every time it hits the End command, making it count up to 50.
                                    While all of this is happening, the Disp A command is displaying
                                    that variable onto the homescreen.  Here's what the finished
                                    program looks like-

                                    EXEC EDIT NEW
                                    1:COUNT
                                    2:COUNT2

                                    ---Make sure EXEC is higlighted---

                                    ---Press Enter when COUNT2 is highlighted---
                                    prgmCOUNT2

                                    ---Press Enter---
                                    prgmCOUNT2
                                                   1
                                                   2
                                                   3
                                                   4

                                    ---And so on until it reaches 50, where the For( loop will stop--
                                                  49
                                                  50
                                                Done

            So, yet again, you've finished another program, and you should be able to understand every
                 little detail about it by now.  However, again, you don't wanna just rush off right
                 here either, you've got plenty to learn young jedi, but the force is strong within you!
                 Fight the dark side and keep on reading!


                              Section 4- Time to CLEAR some things up!
                            \~----------------------------------------~/


            Ok, first things first, you remember that Volume of a Cylinder program I
    showed you earlier that was straight from the book?  Well, now it's time to show
    you how to clean up programs such as those.

                                    PROGRAM:CYLINDER
                                    :Prompt R,H
                                    :&#960;R�H-->V
                                    :Disp "VOLUME IS",V
                                    :

            So, here it is.  I will now guide you step-by-step as to how to shorten
              this program up.


                    1) :Prompt R,H          This first command can't really have much done to it,
                                            this is the smallest you can get it.  The Prompt command
                                            is great for saving space.  It is just like the Input
                                            command, but this one can have multiple inputs.
                                    final size=43

                    2) :&#960;R�H-->V               This is the first place that we can really save a lot of
                                            space, you don't even need this command line to tell you
                                            the truth, so you can just hit that lovely clear
                                            button,delete the command line, and be gone with it.
                                    final size=37

                    3) :Disp "Volume IS",V  Now in this line, you'll need to delete the V from the
                                            end of it, and at &#960;R�H right after the comma.
                                    final size=40

                    4) :                    This spot here is just a blank space that's takin' up a
                                            byte, so you can just delete it from existence.
                                    final size=39

                    So, you've shortened your program down 4 bytes.  That's definitely not a
                    lot, but then again, these aren't exactly the biggest programs in the
                    world either.  This is what your finished program SHOULD look like-

                                    PROGRAM:CYLINDER
                                    :Prompt R,H
                                    :Disp "VOLUME IS",&#960;R�H

                            Congratulations, you've officially made another program that is as small
                            as it could possibly be!  But now, you need to move up yet another level
                            and learn some more programming techniques!


                              Section 5- While loops are just the same
                            \~----------------------------------------~/


            Ok, time for a review.  You've learned two different types of loops right? (For(, Lbl-Goto)
               Now it's time to learn yet another type of loop, the While loop.  These types of loops
               don't automatically add things up, and that's not what they're meant for, these types of
               loops are best for getkey formulas and automatic moving programs (where you have
               multiple sprites moving).  When you use a While loop, you need to type in the While, and
               then type in some sort of equation of some sort, or you can just type in While 1, which
               makes the while loop go on forever. Here is a sample of an easy While loop-

                                    PROGRAM:WHILE
                                    :While 1
                                    :Disp "HI","
                                    :End

                            New Commands used-
                                    While  *Prgm*-`CTL`-5

            Time to break it down-

                    1) :While 1     This is the new command, and all it does here is declares that
                                    you want to create a loop that will continue, unless the
                                    equation after it is not true or valid.  In this equation, it is
                                    asking if 1 is a valid equation (1=valid, 0=invalid), so of
                                    course, it will go on forever, because it is valid=1...kinda
                                    confusing, but it's easy to understand once you get the hang of
                                    it.  So in other words, if you put While 1=0, that would stop on
                                    the first shot, but if you were to put 3<6, that would go
                                    forever.  However, the easiest way to do it is to just put While
                                    1.

                    2) :Disp "HI"," This is a command you've used before, but it is used in a
                                    different sense- When you put a comma after the first quotes, it
                                    will make the text in the second quotes move down a spot, and
                                    start at the beginning.  In the second quotes for this one, it is
                                    just a quote, with nothing after it.  This will make it display
                                    HI every other space, and continously move down forever.

                    3) :End         This is another command you've used before, and all it does is
                                    closes the While loop, and goes back up to the top of it, to
                                    start it over again.

                            Ok, first of all, when you run this program, you will notice that there
                                    is no way to stop it, all you have to do is press ON, and it will cause a
                                    break in the program code and stop immediately there.

                                    EXEC EDIT NEW
                                    :COUNT
                                    :COUNT2
                                    :WHILE

                                    ---Make sure that EXEC is highlighted---

                                    ---Select the WHILE program.---

                                    prgmWHILE

                                    ---Press Enter---

                                    prgmWHILE
                                    HI

                                    HI

                                    HI

                                    HI

                                    ---This will go on forever until you press the ON button---

            Ok, so now you know for loops, lbl loops, and while loops, pretty basic stuff...but
                now I'm going to teach you some more of the slightly more complex commands that
                you use with Input and Output things.


                      Section 6-  Input and Output, not as confusing as they seem
                    \~-----------------------------------------------------------~/

            Now, if you've been following this tutorial section by section, you'll remember
              that in section 4, I made the volume of a cylinder program smalled by rearanging
              some stuff and also getting rid of some other stuff.  What you might not have
              known was that half of that program involved what is called an Input command.
              There are also Outputs, but in this part of the tutorial, I will teach you about
              Input.

            First of all, the command used in the volume of a cylinder program was prompt. Now,
              technically, there are only three commands in the I/O page that are actually
              Input commands:  Input, Prompt, and GetKey.  Input commands, if you have never
              heard of them, are saviors for almost any program, because they allow the person
              using the program to "interact" with it and in a way almost customize it.
              Little did you know it, but every time you press a button, you are sending an
              Input to the calculator's processor, and it quickly decides what to do with that
              button press, and then shows you whatever menu or letter or number which you pressed.

            Ok, so you should get Input commands now, hopefully, because now we're going to use
              that Input knowledge in one of our counting programs which you made in the previous sections.

                                    PROGRAM:COUNT2
                                    :For(A,1,50
                                    :Disp A
                                    :End

            You should remember this program, but if you don't have it, you can make it again from here.
            Now I am going to add one simple line of command, and also modify another line-

                                    PROGRAM:COUNT2
                                    :Input B
                                    :For(A,1,B
                                    :Disp A
                                    :End

            Now I will explain what exactly I did.

                    1) :Input B     Ok, so here's our first Input command, and you're probably
                                    wondering, "What is that?"...first, I hope you read the above
                                    paragraphs, because that'll save me a lot of typing, and second,
                                    the Input command does just what it sounds like, whatever
                                    variable you have after the Input command will come up with a
                                    prompt, in this case looking like this  ?34543 and then you can
                                    type whatever value you want after the question mark.

                    2) :For(A,1,B   This part is the only other part of the program that is different,
                                    if you hadn't noticed.  All I did was replaced the 50 with a B.
                                    Now, whatever the user entered as a value, it will loop that much
                                    and stop at their desired value.  cool, eh?

                                    When you run this program, it will prompt you to enter a number,
                                    like below:

                                    EXEC EDIT NEW
                                    :COUNT
                                    :COUNT2
                                    :WHILE

                                    ---Select COUNT2 and press enter---

                                    prgmCOUNT2

                                    ---Press enter again---

                                    prgmCOUNT2
                                    ?23

                                    ---You can enter whatever value you choose in place of 23---

                                    prgmCOUNT2
                                    ?23
                                                   1
                                                   2
                                                   3
                                                   4
                                    ---Etc. until it reaches whatever the user entered---
                                                  21
                                                  22
                                                  23
                                                Done
                                    
            So, now you know the very basics of taking input, and using it in your own program.
              In the future, you might want to test out inputting two variables, and then putting
              both of the variables in the for loop (just make sure that the first variable isn't
              one of the ones being inputted, or it might mess up).

# License

This repository and its contents are licensed under [CC BY 2.0](http://creativecommons.org/licenses/by/2.0/).

> A chapter of featherless' [digital creative history](https://github.com/featherless/digital-creative-history).
