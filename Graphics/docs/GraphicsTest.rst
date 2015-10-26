Initial Graphics Testing
########################

Once you get your graphics library added to your system, we need to make sure
you can build a graphics program using the tolls I am providing for your class.

Testing Graphics Libraries
**************************

The first thing to do is make sure you can build a graphincs program in
Dev-C++.

Open up the IDE as usual. Then create a new project. This time, we will choose
:menuselection:`File -> New -> Project`. In the window that pops up, click on
the :menuselection:`Multimedia` tab and click on ``freeglut``. Save the
project control file in a new directory (as you should be doing for each
project you se tup). Name it something appropriate.

Once the project has been set up, you will see a screen with a basic template
program loaded. Before you do anything, make sure this test program runs.

Click on :menuselection:`Execute -> Compile and Run`. You will need to save the
``main.cpp`` file before he system will compile and run your program.

WIth any lucj, you will see something like this:

..  image:: GlutDemo.png
    :align" center

The exact demo bmay vary depending on which ``freeglut`` library you loaded. The point of this exercise is to ensure that all the graphics components are in place and working properly. If you see this image (or something similar) you are ready for the next step.

Adding the Class Library
************************

I have created a pair of additional files you need to download onto your system and install in your project folder for class projects:

    * :download:`Gaphics.h`

    * :download:`Graphics.cpp`

FInally, here is a test program that will check that these additional files work:

    * :download:`main.cpp`

Adding this file into your current project will replace the demo code we ran earlier.

In your project, you
