# Create a Website: GitHub Page

## **GitHub Pages**

1. go to [https://pages.github.com/](https://pages.github.com/) 
2. choose "Project site" and "Start from scratch" 
3. follow the instructions

   ![](../../.gitbook/assets/github-pages-setup.png) 

4. upgrade the index.html file with a bit more detail and commit changes

   ```text
   <!DOCTYPE html>
   <html>
     <body>
       <h1>My First Heading</h1>
       <p>My first paragraph.</p>
     </body>
   </html>
   ```

5. upload mp3 to repository, add the audio code to your index.html and commit changes \(Note: my mp3 file was named accordion.mp3 ... so replace that in the code to your mp3 file's name\)

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

6. Add Scratch \(Free, browser-based visual programming language developed by the MIT Media Lab\)
   1. Create a Scratch user account = [https://scratch.mit.edu/join](https://scratch.mit.edu/join)
   2. Complete the following tutorial = [https://scratch.mit.edu/projects/editor/?tutorial=getStarted](https://scratch.mit.edu/projects/editor/?tutorial=getStarted)
   3. Complete another tutorial of your choice.
   4. Create something to embed \(it can be from the tutorial you did or something brand new\)
   5. Click "Share"
   6. click on "copy link" to bring up the embed code ![](../../.gitbook/assets/screen-shot-2020-01-15-at-12.14.17-pm.png) 
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

## GitHub \(general\)

* git learning = [https://try.github.io/](https://try.github.io/) especially [https://learngitbranching.js.org/](https://learngitbranching.js.org/)
* github hello world = [https://guides.github.com/activities/hello-world/](https://guides.github.com/activities/hello-world/)
* [https://github.com/codepath/ios\_guides/wiki/Using-Git-with-Terminal](https://github.com/codepath/ios_guides/wiki/Using-Git-with-Terminal)\*\*\*\*
* \*\*\*\*[https://github.com/benjohansen/benjohansen.github.io/blob/master/index.html](https://github.com/benjohansen/benjohansen.github.io/blob/master/index.html)
* embed video = [https://github.com/etianen/html5media/wiki/embedding-video](https://github.com/etianen/html5media/wiki/embedding-video)

![](../../.gitbook/assets/9ifmj.gif)

[https://stackoverflow.com/questions/18773598/creating-folders-inside-a-github-repository-without-using-git](https://stackoverflow.com/questions/18773598/creating-folders-inside-a-github-repository-without-using-git)

## HTML, CSS, and JavaScript

* understanding HTML, CSS, and JavaScript = [https://jsfiddle.net/isoundart/a7m9v1bz/](https://jsfiddle.net/isoundart/a7m9v1bz/)

