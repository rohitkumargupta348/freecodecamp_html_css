# freecodecamp_html_css

<!-- //freecodecamp_html

//index.html -->
<!DOCTYPE html>

<html lang="en">
  <head>
    
    <title>CatPhotoApp</title>
  </head>
  <body>
    <main>
      <h1>CatPhotoApp</h1>
      <section>
        <h2>Cat Photos</h2>
        <!-- TODO: Add link to cat photos -->
        <p>See more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a> in our gallery.</p>
        <a href="https://freecatphotoapp.com"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back."></a>
      </section>
      <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>cat nip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
          <figcaption>Cats <em>love</em> lasagna.</figcaption>  
        </figure>
        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>  
        </figure>
      </section>
      <section>
        <h2>Cat Form</h2>
        <form action="https://freecatphotoapp.com/submit-cat-photo">
          <fieldset>
            <legend>Is your cat an indoor or outdoor cat?</legend>
            <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor" checked> Indoor</label>
            <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
          </fieldset>
          <fieldset>
            <legend>What's your cat's personality?</legend>
            <input id="loving" type="checkbox" name="personality" value="loving" checked> <label for="loving">Loving</label>
            <input id="lazy" type="checkbox" name="personality" value="lazy"> <label for="lazy">Lazy</label>
            <input id="energetic" type="checkbox" name="personality" value="energetic"> <label for="energetic">Energetic</label>
          </fieldset>
          <input type="text" name="catphotourl" placeholder="cat photo URL" required>
          <button type="submit">Submit</button>
        </form>
      </section>
    </main>
    <footer>
      <p>
        No Copyright - <a href="https://www.freecodecamp.org">freeCodeCamp.org</a>
      </p>
    </footer>
  </body>
</html>

<!-- //css_freecodecamp

//index.html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Colored Markers</title> -->
<!--     <link rel="stylesheet" href="styles1.css"> -->
<!--     <style>
      h1 {
    text-align: center;
  }
  
  .container {
    background-color: rgb(255, 255, 255);
    padding: 10px 0;
  }
  
  .marker {
    width: 200px;
    height: 25px;
    margin: 10px auto;
  }
  
  .cap {
    width: 60px;
    height: 25px;
  }
  
  .sleeve {
    width: 110px;
    height: 25px;
    background-color: rgba(255, 255, 255, 0.5);
    border-left: 10px double rgba(0, 0, 0, 0.75);
  }
  
  .cap, .sleeve {
    display: inline-block;
  }
  
  .red {
    background: linear-gradient(rgb(122, 74, 14), rgb(245, 62, 113), rgb(162, 27, 27));
    box-shadow: 0 0 20px 0 rgba(83, 14, 14, 0.8);
  }
  
  .green {
    background: linear-gradient(#55680D, #71F53E, #116C31);
    box-shadow: 0 0 20px 0 #3B7E20CC;
  }
  
  .blue {
    background: linear-gradient(hsl(186, 76%, 16%), hsl(223, 90%, 60%), hsl(240, 56%, 42%));
    box-shadow: 0 0 20px 0 hsla(223,59%,31%,0.8);
  }
  
    </style>
  </head>
  <body>
    <h1>CSS Color Markers</h1>
    <div class="container">
      <div class="marker red">
        <div class="cap"></div>
        <div class="sleeve"></div>
      </div>
      <div class="marker green">
        <div class="cap"></div>
        <div class="sleeve"></div>
      </div>
      <div class="marker blue">
        <div class="cap"></div>
        <div class="sleeve"></div>
      </div>
    </div>
  </body>
</html> -->

<!-- //styles1.css
h1 {
    text-align: center;
  }
  
  .container {
    background-color: rgb(255, 255, 255);
    padding: 10px 0;
  }
  
  .marker {
    width: 200px;
    height: 25px;
    margin: 10px auto;
  }
  
  .cap {
    width: 60px;
    height: 25px;
  }
  
  .sleeve {
    width: 110px;
    height: 25px;
    background-color: rgba(255, 255, 255, 0.5);
    border-left: 10px double rgba(0, 0, 0, 0.75);
  }
  
  .cap, .sleeve {
    display: inline-block;
  }
  
  .red {
    background: linear-gradient(rgb(122, 74, 14), rgb(245, 62, 113), rgb(162, 27, 27));
    box-shadow: 0 0 20px 0 rgba(83, 14, 14, 0.8);
  }
  
  .green {
    background: linear-gradient(#55680D, #71F53E, #116C31);
    box-shadow: 0 0 20px 0 #3B7E20CC;
  }
  
  .blue {
    background: linear-gradient(hsl(186, 76%, 16%), hsl(223, 90%, 60%), hsl(240, 56%, 42%));
    box-shadow: 0 0 20px 0 hsla(223,59%,31%,0.8);
  }
  
 -->
