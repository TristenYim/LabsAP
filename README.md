# LabsAP
Labs for AP Computer Science.

These labs are from 2015.  I have not tested the repo yet to make sure that you can run the projects.

There are three projects.
* Magpie - a text-based chat bot
* pixLab - a picture editing exercise
* Elevens - a solitaire card game

Each of the labs has code and directions.  There are instructions in the files in the main repository.  The src folder has subfolders with the different folders in them.  Each of these folders may have subfolders too.

Just fork the repository and do the exercises.  At least that is what I hope is all you need to do.

## More info

After forking the repository (which makes a copy of my repository to your account), clone the repo to your own computer.  (Using your IDE ought to be easy.)

### For IntelliJ users

Make a New Project from Existing Sources.  Then, browse to the folder that has the particular project you want to work on.  (pixLab, Elevens-Ativity Starter Code, or Magpie-ActivityStarterCode)  Select this folder and IntelliJ will make your project for you.

When you are opening picture files, you will probably need to change the folder where you are looking.  For instance, in the PixLab, PictureExplorer main method, you will probably need to change the line:

```Picture pix = new Picture("beach.jpg");```

to

```Picture pix = new Picture("images/beach.jpg");```

### Other IDE users

I would imagine the process is similar to the process for IntelliJ.  Sorry that I do not have more specific instructions.
