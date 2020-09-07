# During Class

## **Add Styling \(we'll do this during our class meeting\)**

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

