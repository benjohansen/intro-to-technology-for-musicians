# scratch



## Tips

* embed video = [https://github.com/etianen/html5media/wiki/embedding-video](https://github.com/etianen/html5media/wiki/embedding-video)
* working with directories \(folders\)

![](../.gitbook/assets/9ifmj.gif)

[https://stackoverflow.com/questions/18773598/creating-folders-inside-a-github-repository-without-using-git](https://stackoverflow.com/questions/18773598/creating-folders-inside-a-github-repository-without-using-git)

## Reloading page \(and empty cache\)

* Chrome:
  * View &gt; Developer &gt; Developer Tools
  * right click on the reload button and a menu will drop down

{% hint style="warning" %}
[https://support.zendesk.com/hc/en-us/articles/219161157-Options-to-clear-cache-and-cookies](https://support.zendesk.com/hc/en-us/articles/219161157-Options-to-clear-cache-and-cookies)
{% endhint %}

## How to add a Scratch

Add Scratch \(Free, browser-based visual programming language developed by the MIT Media Lab\)

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

