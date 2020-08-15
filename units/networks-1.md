# 3. Networks

Great Resource: [How the Internet Works](https://www.youtube.com/playlist?list=PLzdnOPI1iJNfMRZm5DDxco3UdsFegvuB7) \(40min worth of videos\) and [An Introduction to Computer Networks](http://intronetworks.cs.luc.edu/current2/html/intro.html) \(textbook\)

1. **In what type of format is everything \(text, photos, videos, etc.\) encoded to transfer them between connections of the internet \(regardless the medium\)? How does that physically travel down a metal wire? How does that physically travel down a fiberoptic \(glass\) wire?**
2. Define bandwidth. How is the size of bandwidth described?
3. Define packets \[of information\] - what is included in a packet? \(hint: use mail as an analogy\) Discuss the importance of TCP.
4. What are modems and routers?
   * [difference between modems and router](https://www.lifewire.com/difference-between-modem-and-router-4159854)
5. Discuss the difference between IP and MAC addresses. \(include the term “DNS” in your answer\).
6. Describe the difference between HTML, CSS, and Javascript.
   * [HTML vs CSS vs JavaScript:](https://blog.hubspot.com/marketing/web-design-html-css-javascript)
     * **HTML** provides the basic structure of sites, which is enhanced and modified by other technologies like CSS and JavaScript.
     * **CSS** is used to control presentation, formatting, and layout.
     * **JavaScript** is used to control the behavior of different elements.
     * [https://jsfiddle.net/isoundart/a7m9v1bz/](https://jsfiddle.net/isoundart/a7m9v1bz/)

## Create a Github "Webpage"

{% hint style="danger" %}
Screen shots below are difficult to see ... so press Command+ on a Mac \(Ctrl+ on PC\) as many times as you need to zoom in on this page.
{% endhint %}

* git learning = [https://try.github.io/](https://try.github.io/) especially [https://learngitbranching.js.org/](https://learngitbranching.js.org/)
* github hello world = [https://guides.github.com/activities/hello-world/](https://guides.github.com/activities/hello-world/)
* [https://github.com/codepath/ios\_guides/wiki/Using-Git-with-Terminal](https://github.com/codepath/ios_guides/wiki/Using-Git-with-Terminal)\*\*\*\*

1. create a GitHub account = [https://github.com/join](https://github.com/join)
2. create a new repository

   ![](../.gitbook/assets/screen-shot-2020-01-15-at-3.48.52-pm.png) 

   > \*\*\*\*
   >
   > **A "repository" is like a folder for your project.**
   >
   > \*\*\*\*

3. create a new file

   ![](../.gitbook/assets/screen-shot-2020-01-15-at-3.50.28-pm.png) 

4. name new file "index.html," add the code below, and "commit new file"

   ![](../.gitbook/assets/index.png) 

   ```text
   <!DOCTYPE html>
   <html>
     <body>
       <h1>My First Heading</h1>
       <p>My first paragraph.</p>
     </body>
   </html>
   ```

   > **a "commit" is like saving the changes to your files, but GitHub saves all of your commits so you can always go back to any "version" or "revision" of your files**
   >
   > \*\*\*\*

5. make site published using GitHub Pages
   * click on your repository "Settings" tab

     ![](../.gitbook/assets/screen-shot-2020-01-15-at-3.52.11-pm.png) 

   * change the "Source" to "master branch"

     ![](../.gitbook/assets/screen-shot-2020-01-15-at-3.52.24-pm.png) 

   * now your URL is displayed

     ![](../.gitbook/assets/screen-shot-2020-01-15-at-3.53.04-pm.png) 
6. upload mp3 to repository

   ![](../.gitbook/assets/screen-shot-2020-01-15-at-4.02.24-pm.png) 

7. click edit on your index.html file

   ![](../.gitbook/assets/screen-shot-2020-01-15-at-3.53.31-pm%20%281%29.png) 

8. insert the &lt;audio&gt; tag code to your index.html \(including &lt;div&gt; tags\) somewhere in the &lt;body&gt; of your page and commit changes \(Note: my mp3 file was named accordion.mp3 ... so edit the code to show your mp3 file's name\)

   ```
   <!DOCTYPE html>
   <html>
     <body>
       <h1>My First Heading</h1>
       <p>My first paragraph.</p>
    
       <div>
         <audio controls>
             <source src="accordion.mp3" type="audio/mpeg">
             Your browser does not support the audio tag.
         </audio>
       </div>
    
     </body>
   </html>
   ```

9. Add Scratch \(Free, browser-based visual programming language developed by the MIT Media Lab\)
   1. Create a Scratch user account = [https://scratch.mit.edu/join](https://scratch.mit.edu/join)
   2. Complete the following tutorial = [https://scratch.mit.edu/projects/editor/?tutorial=getStarted](https://scratch.mit.edu/projects/editor/?tutorial=getStarted)
   3. Complete another tutorial of your choice.
   4. Create something to embed \(it can be from the tutorial you did or something brand new\)
   5. Click "Share"
   6. click on "copy link" to bring up the embed code ![](../.gitbook/assets/screen-shot-2020-01-15-at-12.14.17-pm.png) 
   7. add Scratch iframe to your index.html in GitHub and commit the changes

      ```
      <!DOCTYPE html>
      <html>
        <body>
          <h1>My First Heading</h1>
          <p>My first paragraph.</p>
    
          <div>
            <audio controls>
                <source src="accordion.mp3" type="audio/mpeg">
                Your browser does not support the audio tag.
            </audio>
          </div>
    
          <iframe src="https://scratch.mit.edu/projects/359828492/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>
    
        </body>
      </html>
      ```

## Add Styling \(we'll do this during our class meeting\)

1. create another new file in the same directory \(folder\) as your index.html file
2. name the file style.css
3. add the following code to the style.css file

   ```text
   h1 {
     font-size: 10em; /* 1em = 12pt = 16px */
     font-family: "Comic Sans MS", cursive, sans-serif;
     color: blue
   }

   p {
     font-family: Courier, Monaco, monospace;
     color: brown
   }
   ```

4. add a header in your index.html file so that it knows where to get the styling code

   ```text
   <!DOCTYPE html>
   <html>
  
     <head>
       <title>benjohansen</title>
       <meta charset="utf-8" />
       <link rel="stylesheet" href="style.css?version=2" />
     </head>

     <body>
       <h1>My First Heading</h1>
       <p>My first paragraph.</p>
    
       <div>
         <audio controls>
             <source src="accordion.mp3" type="audio/mpeg">
             Your browser does not support the audio tag.
         </audio>
       </div>
    
       <iframe src="https://scratch.mit.edu/projects/359828492/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>
    
     </body>
   </html>
   ```

## Tips

* embed video = [https://github.com/etianen/html5media/wiki/embedding-video](https://github.com/etianen/html5media/wiki/embedding-video)
* working with directories \(folders\)

![](../.gitbook/assets/9ifmj.gif)

[https://stackoverflow.com/questions/18773598/creating-folders-inside-a-github-repository-without-using-git](https://stackoverflow.com/questions/18773598/creating-folders-inside-a-github-repository-without-using-git)

## Reloading page \(and empty cache\)

* Chrome:
  * View &gt; Developer &gt; Developer Tools
  * right click on the reload button and a menu will drop down



