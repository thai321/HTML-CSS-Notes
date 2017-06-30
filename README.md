# HTML-CSS-Notes


## HTML template
```HTML
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
  <body>

  </body>
</html>
```


## Link

```HTML
  <a href="#"></a>
```

## image

```HTML
<img src="" alt="Name of the image" >
```

## Audio Files
```HTML
<audio controls>
    <source src="audio/name.mp3" type="audio/mp3">
    <source src="audio/name.ogg" type="audio/ogg">
    <a href="audio/name.mp3">Audio recording</a>
</audio>
```

## Video Files
```HTML
<video>
  <source src="video/example.mp4" type="video/mp4">
  <source src="video/example.webm" type="video/webm">
  <source src="video/example.ogv" type="video/ogg">
    Your web browser is outdated and does not support
    HTML video. Please consider <a href="http://..."> Updating</a>
</video>
```

## Header
```HTML
<h1></h1>
<h2></h2>
<h3></h3>
<h4></h4>
<h5></h5>
<h6></h6>
```


## List
### UnOrdered List
```HTML
  <ul>
    <li></li>
    <li></li>
  </ul>
```
### Ordered List
```HTML
  <ol>
    <li></li>
    <li></li>
  </ol>
```

### Description List
```HTML
  <dl>
    <dt></dt>
    <dt></dt>
  </dl>
```

## Bold
```HTML
  <strong>Example</strong>
```

## Italic
```HTML
  <em>Example text</em>
```

## Special Character
```HTM
- Right signle quote: &rsquo;
- Left signle quote: &lsquo;
- Right Double quote: &rdquo;
- Ampersands: &amp;
- Greater than: &gt;
- Less than: &lt;
- Copyright: &copy;
- Registered symbol: &reg;
- Trademark symbol: &trade;
```

## Navigation
```HTML
<nav>
  <ul>
    <li><a href="index.html">Home</a></li>
    <li><a href="about.html">About</a></li>
  </ul>
</nav>
```

## Non-Semantic Structural
```HTML
  <div>
    Block-level
  </div>

  <span>Inline</span>
```

## Form
```HTML
  <form >
    <label for="firstName">First Name:</label>
    <input id="firstName" type="text" name="firstName" >

    <label for="email">Email:</label>
    <input id="email" type="email" name="email">

    <label for="telephone">Telephone:</label>
    <input id="telephone" type="tel" name="telephone">

    <label for="yourMessage">Message:</label>
    <textarea id="yourMessage" name="yourMessage" rows="8" cols="80"></textarea>

    <input type="submit" value="Submit">
  </form>
```

## Set of option: Select(dropdown), Radio, Checkbox
```HTML
  <label for="favoriteColor">What is yoru Favorite Color?</label>
  <select id="favoriteColor" name="favoriteColor">
    <option value="colorRed">Red</option>
    <option value="colorGreen">Green</option>
    <option value="colorBlue">Blue</option>
  </select>

  <fieldset>
    <legend>Which meals do you enjoy? (choose one)</legend>
    <input type="radio" id="breakfast" name="favoriteMeal" value="meal1"><label for="breakfast">Breakfast</label>
    <input type="radio" id="brunch" name="favoriteMeal" value="meal2"><label for="brunch">Breakfast</label>
    <input type="radio" id="lunch" name="favoriteMeal" value="meal3"><label for="lunch">Breakfast</label>
  </fieldset>

  <fieldset>
    <legend>Which meals do you enjoy? (Check all that apply)</legend>
    <input type="checkbox" id="breakfast" name="favoriteMeal" value="meal1"><label for="breakfast">Breakfast</label>
    <input type="checkbox" id="brunch" name="favoriteMeal" value="meal2"><label for="brunch">Breakfast</label>
    <input type="checkbox" id="lunch" name="favoriteMeal" value="meal3"><label for="lunch">Breakfast</label>
  </fieldset>
```

## table
```HTML
  <table>

    <thead>
      <tr>
        <th>Name</th>
        <th>Quantity</th>
      </tr>
    </thead>

    <tbody>
      <tr>
        <td>Bread</td>
        <td>2</td>
      </tr>

      <tr>
        <td>Milk</td>
        <td>1</td>
      </tr>
    </tbody>

    <tfoot>
      <tr>
        <td>Total</td>
        <td>3</td>
      </tr>
    </tfoot>

  </table>
```
