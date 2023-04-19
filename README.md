# intro-to-r
  R is an open source language that is commonly used for statistical data analysis. Not only does it provide a highly extensive and flexible set of tools for analysis and graphical visualization, it is also relatively straightforward to use, and best of all: free!
  Below we will show you how to download and set up R and RStudio as well as some basic techinques to get under your belt.

## Installing R

  This process looks slightly different depending on the operating system that you use. Windows, Mac, and Linux users to first navigate to the site below and follow instructions from the set up wizard to complete download and installation.
  [https://cloud.r-project.org/](https://cloud.r-project.org/)

After you have installed it, I would recommend booting up the R console and testing it out with some simple commands. You can find it by clicking on the "R" app icon or searching it up in your computer's search bar.
Here we have opened up the RConsole and ran a very simple line
```R
plot(1:10)
```
<img width="700" alt="Screen Shot 2023-03-29 at 12 57 30 PM" src="https://user-images.githubusercontent.com/104386126/228614394-5d9398b2-1666-461c-b1b9-8056d9b88902.png">


## Installing RStudio

  To recap before downloading it, R Studio is an Integrated Development Enviroment(IDE) that offers a more user friendly platform to utilize R. Make no mistake, you can fully use R in the R Console that we showed above (and many people do!). However, many others prefer to use R Studio as it has a nicer interface and incorporates many other useful features in addition to the console, like script editors, R markdown and Git Hub integration. Like R, RStudio is also fully free to use.
(Note: You need to install R before you can use RStudio)

  MacOS and Windows users can click this link and follow instructions on the site to download and setup RStudio. [https://posit.co/download/rstudio-desktop/](https://posit.co/download/rstudio-desktop/)

After setting up the IDE you should get a workspace that looks similar to this. 

<img width="700" alt="Screen Shot 2023-03-29 at 2 03 56 PM" src="https://user-images.githubusercontent.com/104386126/228628251-e2736a10-92cf-4f7b-8282-e7e8f7ab115f.png">

You can type code directly into the console after the ">" command prompt. For example, in the image below we typed 1+1 and after pressing enter, R returned 2.
```R
>1+1
[1] 2
>
```

<img width="700" alt="Screen Shot 2023-04-18 at 11 01 54 PM" src="https://user-images.githubusercontent.com/104386126/232955972-4c7dce96-73e6-4dad-8d66-37995b64a652.png">

However, typing code in line by line can get confusing and hard to keep track of the larger your projects get. There is the option to write all your R code in an R script file which contains all your code as plain text. Click "File", "New file", and select "R script"

<img width="700" alt="Screen Shot 2023-04-18 at 10 58 26 PM" src="https://user-images.githubusercontent.com/104386126/232955806-89ce99f4-e3c2-47a0-82fc-cba6f5b7f615.png">
