# Code Journey - Log
## By: Chris Krygier

### Day 0: April 29, 2022

**Today's Progress**: Investigated Sphinx, MyST and Markdown using Talk To Me Python Course on Sphinx and Markdown.

**Thoughts**:


### Day 1: April 30, 2022

**Today's Progress**: I refreshed on Basic HTML and HTML5 Syntax by completing 14 of the 28 Basic HTML and HTML5 challenges. 


**Thoughts**: I investigated other code challenges using the #100DaysOfCode hashtag. 

Link to Work: 
 Course: https://www.freecodecamp.org/learn/responsive-web-design/

 ### Day 2: May 1, 2022

 **Today's Progress**: I finished the Basic HTML and HTML5 portion of the Reponsive Web Design course on freecodecamp

 **Thoughts**: I continue to push through finishing up the first portion of the HTML and HTML5.

 Links:
 <a href="https://www.freecodecamp.org/learn/responsive-web-design"> Reponsive Web Design Course on FreecodeCamp</a>

 ### Day 3: May 2, 2022

 **Today's Progress**: I completed 29 exercises of the Basic CSS course (responsive Web Design). 

 **Thoughts**: Things I learned awhile back are coming back after using the language. 

 Links:

### Day 4: June 5, 2022

**Today's Progress**: I finished chapter 7 in Learn Powershell in a month of lunches. I completed the exercises at the end of the chapter. I learned how to install and import modules from the Powershell Gallery. I installed the PSWindowsUpdate and PSScriptTools modules into my powershell environment. One of the exercises required me to create 10 text files and use Compare Object to determine which file names were different. Additionally, I setup my script environment last night to use the following tools - Powershell Core, Windows Terminal, Neovim, Nerd Fonts, Scoop (command line installer), PSReadLine. 

**Thoughts**: I wished I learned PSReadLine earlier in my career as it would have remembered my powershell history. Additionally, I believe that I have fallen into the rabbit hole of customizing my shell instead of performing code snippets. I am really enjoying the powershell book. Once I complete the challenge of reading a chapter a day. I will see about reading Learn Powershell Scripting in a Month of Lunches or Practical Automation with Powershell. Additionally, I may start the Powershell Cookbook 4th Edition which covers Powershell Core. 

### Day 5: June 6th, 2022

**Today's Progress** Finished reading chapter 8 in Learn Powershell in a Month of Lunches. Completed the exercises without looking at the answer section. Worked with CSS and HTML for a upcoming work project.

**Thoughts**: I am throughly enjoying the Powershell book as it is impacting my work life currently. The ability to retrieve information automatically without using a GUI and piping it to a file format in which I can give to other IT individuals and management. I am still dreading learning the website management that is required for updating our work website. 

### Day 6: June 7th, 2022

**Today's Progress**: I finished chapter 9 in Learn Powershell in a Month of Lunches. It went over how they would tackle a problem using the following steps:

1) Use Get-Command to see if there is a command for the task that is presented
2) Use Find-Module to see if there is a module that will assist with the task
3) Use Help files about the cmdlets and modules that are found
4) Test in a virtual environment to see if commands work without causing issues.
5) Check Object Type when passing data to pipeline.

**Thoughts**: This was a good chapter as it showed the process of how to tackle a given IT task using only powershell

### Day 7: June 8th, 2022

**Today's Progress**: I finished chapter 10 in Learn Powershell in a Month of Lunches. The chapter focused on how to use the pipeline correctly. There are two methods of piping data from one cmdlet to another. The methods are below:

1) ByValue
2) ByPropertyName

You can use a hashtable with Select-Object that will assist with matching given properties with the additional cmdlets.

**Thoughts**: This chapter was somewhat difficult to understand at first. I had to keep looking at the examples in the book and follow along. The lab exercies at the end made me think if the commands that were given would complete correctly. 

### Day 8: June 9th, 2022

**Today's Progres**: I finished chapter 11 in Learn Powershell in a MOnth of Lunches. The chapter focused on formatting objects. We learned the following about the following cmdlets: Format-Table, Format-List, and Format-Wide. Additionally, a scripter will always put the format commands on the right as the cmdlets will create formatting objects which will feed into Out-File, Out-Default, Out-Host.

**Thoughts**: I liked the chapter and the exercies. I learned how to use the name and expression command when talking about certain properties. Such as converting Working Set memory to MB or GB instead of bytes. 
@{n='WorkingSetMB'; expression={$_.WorkingSet / 1MB -as [int]}}

### Day 9: June 10th, 2022

**Today's Progress**: I finished chapter12 in Learn Powershell in a Month of Lunches. The chapter was focused on filtering objects from the pipeline. There are two ways in which you can filter data from powershell. You can use the Where-Object or Select-Object cmdlets. I finished all the exercises using the Where-object method. Some of the examples included only list files that are larger than 5MB in size in current directory. Additionally, it asked for all files that have a lastwritetime of -7 days or greater. 

**Thoughts**: I really enjoyed the chapter. I can see the benefit of using the filter options in my daily IT tasks. I plan on using some when I go back to work on Monday.

### Day: 9: June 11th, 2022

**Today's Progress**: I finished chapter 13 in Learn Powershell in a Month of Lunches. The chatper was focused on remoting to different workstations. You had two methods in which you can remote into a given workstation:

1) Use WsMan if the workstation is Windows based; however, it will not work with non-Windows workstations
2) Use Powershell Over SSH - This method is accepted by all versions after Powershell 7.1. 

**Thoughts**: I liked the chapter has I performed remote powershell before as I always run Enable-PSremoting on my workstations at the office. I could not really test at home as I was not on the domain and it does require a difficult setup 

### Day 10: June 12th, 2022

**Today's Progress**: I finished Chapter 14 in Learn Powershell in a Month of Lunches. The chapter was focused on using background jobs. You had two types of Job to perform

1) Start-Job is used if you have a long running command that will take some time to complete
2) Start-ThreadJob is used if you have a command that will not need a lot of time to complete and use the current pwsh thread.

**Thoughts**


## Day 11: June 13th, 2022

**Today's Progress**:

**Thoughts**:
