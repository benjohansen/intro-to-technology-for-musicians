# Create a Website: GitHub Page

## **GitHub Pages**

1. create a GitHub account = [https://github.com/join](https://github.com/join)
2. go to [https://pages.github.com/](https://pages.github.com/) 
3. choose "Project site" and "Start from scratch" 
4. follow the instructions

   ![](../../.gitbook/assets/github-pages-setup.png) 

5. upgrade the index.html file with a bit more detail and commit changes

   ```text
   <!DOCTYPE html>
   <html>
     <body>
       <h1>My First Heading</h1>
       <p>My first paragraph.</p>
     </body>
   </html>
   ```

6. upload mp3 to repository, add the audio code to your index.html and commit changes \(Note: my mp3 file was named accordion.mp3 ... so replace that in the code to your mp3 file's name\)

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

7. Add Scratch \(Free, browser-based visual programming language developed by the MIT Media Lab\)
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

