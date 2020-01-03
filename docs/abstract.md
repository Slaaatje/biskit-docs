<!-- Hotjar Tracking Code for https://ruud.koek.link/biskit/docs/#/ -->
<script>
    (function(h,o,t,j,a,r){
        h.hj=h.hj||function(){(h.hj.q=h.hj.q||[]).push(arguments)};
        h._hjSettings={hjid:1623350,hjsv:6};
        a=o.getElementsByTagName('head')[0];
        r=o.createElement('script');r.async=1;
        r.src=t+h._hjSettings.hjid+j+h._hjSettings.hjsv;
        a.appendChild(r);
    })(window,document,'https://static.hotjar.com/c/hotjar-','.js?sv=');
</script>
<br><br>

# Abstract
[Abstract](https://www.abstract.com) brings git-inspired version control & collaboration to your
 design team.

<img src="_images/Abstract.png" alt="Abstract" />

*Example of how Abstract works*
<br>

 ***



## Basics
- The master branch contains only designs that are approved by the design team and the client. It is not used for experiments and stuff that is not 100% certain to go to the development stage of the project.
- It's recommended to work in different artboards. This way you prevent a lot of merge conflicts.
- How you should work: Make artboards with different iterations and make a commit. When a iterations is agreed upon by the client and team, delete all other artboards and commit again. This way all iterations are saved (in the activity history) but the file is not cluttered with experiments. 
<br>

 ***

## Branches
- Always make a branch from the master file. This way we will have one source of truth at any time
- Create branches for specific purposes, this provides transparency to the team. Name the branch the way the ticket in Trello is named or name it something that is clear to everybody, so it's easy to reference later.  (For exmaple: instead of 'Marijn's Branch' go for 'Experiment with Hero size')
- Only update to master once the ticket is fully approved and reviewed
- Not all of your proposed changes will ultimately make it back to the Master. But those concepts can still end up being useful down the road. Branch Archives allow you to capture explorations that you might want to revisit later.
- When merge conflicts arise, please involve your team members when necessary to make the right decisions. Abstract doesn't provide the ability to pick and choose elements. It only allows you to pick one of two artboards or symbols.

<img src="_images/Branches-naming.png" alt="Abstract - Branches" 
alt="Example Atomic Design" style="float: left; height:325px; margin-left: -10px;" /> 
<img src="_images/Branches.gif" alt="Abstract - Branches" 
alt="Example Atomic Design" style="float: left; width:555px; margin-top: 5px;" /> 



<br><br><br><br><br><br><br><br><br><br><br><br><br><br>

 ***
## Shared Libraries
**A single source of truth for your design system.**

A Library is a Sketch document that contains Symbols that can be used globally. You can share the Library by storing to Abstract. As a result, your teammates can have access to the same Libraries.

When you update any Symbol in that Library, everyone that are using that Library will receive a notification on the far top right of Sketch's UI. Like this, their Libraries will be always in sync! 

<img src="_images/update-sketch.png" alt="Abstract - Branches" 
alt="Example Atomic Design" style="float: left; height:225px;" />

<br><br><br><br><br><br><br><br><br>

Using Linked Libraries, you can truly work with one single source of truth. Example: Our products works with multi
platforms like mobile and web, and they all use the same set of icons. Now all those projects can all use the same
set of icons. Update an icon and the changes will propagate throughout wherever they’re being used. And thanks to
the way Abstract works, there’s a transparent paper trail of who made which changes and why, plus an easy way to
revert changes if needed.

**How to add a linked library**

1. Make sure you have your Library file(s) set up ([learn how](https://www.abstract.com/help/libraries/add-library/))
2. Go to the project you want to link this Library file to.
3. On the “Files” tab, click “Add File” and select “Link Library…”
4. In the window that appears, click on a project, select a Library file, and click “Link Library”.
<br><br>

 ***

## Commits
- Try to make commits of every milestone in the design process. You can always go back to previous commits. This also means you don't have to worry about deleting stuff, and thus keeping the file clean: You can always go back to previous state.
- Always try to be descriptive about what you did. This way everyone can see clearly what the commit contains, for future reference. Use a clear title and a description with a brief explanation of the things you've done.
<br><br>
        
***

## Reviews & Comments
Abstract has multiple ways to gather feedback from both colleagues as clients.
 
<img src="_images/abstract-comment.gif" alt="Abstract - Comment" 
alt="Example Atomic Design" style="float: left; width:720px;" />
<br>

*Example of how Reviews & Comments work*
<br>

 ***

### Sources
 <a href="https://uxplanet.org/mastering-the-abstract-workflow-b204e28e335c" target="_blank">
<img src="_images/medium-abstract2.png" alt="Medium - Abstract" 
 style="float: left; width:730px; margin-left: -10px;" /></a>
 <br><br><br><br><br><br><br><br>
 
 
 

