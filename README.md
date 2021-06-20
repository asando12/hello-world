# hello-world
Beginning repository  

Hello

I just put this together to get some exprience with Github.  It's very intresting to see what you can do.
I've have been able to get some reading done about what I can perform.

<main>
  <h1> Some tech </h1>
  
<a href="" alt="placecard"> </a> 
  
  <img src="http://clipart-library.com/clipart/381624.htm" alt="World clip art"> 
  
  <ol>
    <li> This is a list att. </li>
    <li> I Got one </li>
    
  </ol>
  
form action  Input type  Placeholder 
 <form action="https://www.freecatphotoapp.com/submit-cat-photo"> 
   
<input type="text" placeholder="cat photo URL">

This is the button code for adding on page 
  <button type="submit">Submit</button>

  

Radio Buttons:

You can use radio buttons for questions where you want the user to only give you one answer out of multiple options.

Radio buttons are a type of input.

Each of your radio buttons can be nested within its own label element. By wrapping an input element inside of a label element it will automatically associate the radio button input with the label element surrounding it.

All related radio buttons should have the same name attribute to create a radio button group. By creating a radio group, selecting any single radio button will automatically deselect the other buttons within the same group ensuring only one answer is provided by the user.

Here's an example of a radio button:
  
  
  <label>
      <input type="radio" name="indoor-outdoor">Indoor
      </label>

      <label>
      <input type="radio" name="indoor-outdoor">Outdoor
      </label>
  
  
  Create a Set of Checkboxes
Forms commonly use checkboxes for questions that may have more than one answer.

Checkboxes are a type of input.

Each of your checkboxes can be nested within its own label element. By wrapping an input element inside of a label element it will automatically associate the checkbox input with the label element surrounding it.

All related checkbox inputs should have the same name attribute.

It is considered best practice to explicitly define the relationship between a checkbox input and its corresponding label by setting the for attribute on the label element to match the id attribute of the associated input element.

Here's an example of a checkbox:

<label for="loving"><input id="loving" type="checkbox" name="personality"> Loving</label>
  
  
  
  
  </form>
  
  Define the Head and Body of an HTML Document
You can add another level of organization in your HTML document within the html tags with the head and body elements. Any markup with information about your page would go into the head tag. Then any markup with the content of the page (what displays for a user) would go into the body tag.

Metadata elements, such as link, meta, title, and style, typically go inside the head element.

Here's an example of a page's layout:

<!DOCTYPE html>
<html>
  <head>
    <meta />
  </head>
  <body>
    <div>
    </div>
  </body>
</html>

  
Working on style CSS
  
  <style>
  .red-text {
    color: red;
    font-size: 3rem;
    font-family: "open sans";
    font-weight: normal;
    font-style: italic;
  }
</style>

 .thick-green-border {
    border-color: green;
    border-width: 10px;
    border-style: solid;
    border-radius: 50%;
  }

  .smaller-image {
    width: 100px;
  }

  .silver-background {
    background-color: silver;
    background: linear-gradient(green, white)
  
  #cat-photo-form {
  background-color: green;
  }
  
   .box {
    border-style: solid;
    border-color: black;
    border-width: 5px;
    text-align: center;
  }

  .yellow-box {
    background-color: yellow;
    padding: 20px 40px 20px 40px;
  }

  .red-box {
    background-color: crimson;
    color: #fff;
    margin: 20px 40px 20px 40px;
  }
  
  <style>
  body {
    background-color: black;
    font-family: monospace;
    color: green;
  }
</style>
<h1>Hello World!</h1>
  
