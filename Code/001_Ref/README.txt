HTML Important information:

  Elements:
    1- html
    2- head
    3- meta
    4- title
    5- body


  Tags:
    1- <html>
    2- <head>
    3- <meta>
    4- <title>
    5- <body>


  Opening and Closing tags:
    1- <html></html>
    2- <head></head>
    3- <title></title>
    4- <body></body>


  Self Closing tags:
    1- <meta>
    2- <link>
    3- <hr>
    4- <br>
    5- <img>
    6- <input>
    7- <source>
    8- <embed>
    9- <param>
    10- <wbr>

  Nested Tags:
      <!DOCTYPE HTML>
      <html>
      <head>
         <meta charset="UTF-8">
      </head>
      <body>

      </body>
      </html>

      1- The child element of html = head, body
      2- The parent element of body = html
      3- The sibling of the head tag = body
      4- The root = html
      5- Doctype = declaration NOT an element

   Synonyms:
      1- Web page = html document, html page, document
      2- Parent = ancestor
      3- Child = descendent

   Separation of concerns:
      1- HTML -> Structure
      2- CSS  -> Formatting
      3- JS   -> Functionality

      _________________________
      |                       |
      |       <header>        |
      |_______________________|


       _______________________
      |                       |
      |       <section>       |
      |    ________________   |            ________________
      |   |   <article>    |  |           |                |
      |   |________________|  |           |     <aside>    |
      |_______________________|           |________________|

      ________________________
      |                       |
      |       <footer>        |
      |_______________________|



  Semantics of html:
    <header></header>

    <section>
      <article></article>
    </section>

    <aside></aside>

    <footer></footer>


  Layout resourses:
    https://css-tricks.com/snippets/css/a-guide-to-flexbox/
    http://learnlayout.com

  Entities:
    - &nbsp; (When you dont want the text to break)
---------------------------------------------------------------------------

  CSS Important information:
    1- Selector - declaration block - declarations - property: value

  example:
    h1 {
      text-align: center;
    }

    2- External CSS Order: reset - main.css - media-query
    3- Tools: 
      - Flexbox
      - Position
      - Float (float:right, left, none) (overflow: auto ) (clear: both)
---------------------------------------------------------------------------

-Display property:


  block: 
    - Begins on a new line
    - Takes up the entire width
    - You can nest inside -> inline and block elements

  inline:
    - does not begin in a new line
    - take up the content's width
    - you can nest: inline elements

    div is a: 
     - block element

    span is an: 
     - inline element 

---------------------------------------------------------------------------

-Position


static:
    - It overwrites all the positions
    - Every element has a static position by default
    - It follows the flow of the document
    - top, right, bottom, left are not applicable

relative:
    - It follows the flow of the document like static
    - but top, right, bottom, left are applicable

absolute:
    - It does not follow the flow of the document
    - Other elements will behave as this element is not even there
    - It works in relationship to some other elements up the DOM

fixed:
    - It does not follow the flow of the document like absolute
    - Not affected by scrolling (The document flows under the element)

sticky:
    - It works as the relative
    - It sticks when scrolling (Used for sticky navs)

---------------------------------------------------------------------------
- Short hand:
  - I Personally Say Regular Apples Come On Colors

- Background Property:

      background-image
      background-position
      background-size
      background-repeat
      background-attachment
      background-clip
      background-origin
      background-color: 

---------------------------------------------------------------------------

Note: 
- The axis position depends on row || column positions.

- Flexbox (Display: flex;) 

1- justify-content:
  - flex-start
  - flex-end
  - center
  - space-around
  - space-between

2- align-items:
  - flex-start 
  - flex-end
  - center
  - baseline
  - stretch

3- flex-direction:
  - row
  - row-reverse
  - column
  - column-reverse

4- order: positions the elements from left to right
  - 0 (defaul)
  - 1
  - -1

5- align-self: works like align-items but for a specific item.
  - flex-start 
  - flex-end
  - center
  - baseline
  - stretch

6- flex-wrap: wraps the elements to a new line
  - wrap
  - nowrap
  - wrap-reverse

7- flex-flow: shorthand (<flex-direction> && <flex-wrap>)
  - row wrap
  - column nowrap

8- align-content:
- aligns a flex container's lines within the flex container
when extra space in the cross axis.

- flex-start
- flex-end
- center
- space-between
- space-around
- stretch

---------------------------------------------------------------------------

  Tools:
    - Adobe kuler
    - pexels
    - unsplash
    - istock photos
    - colors mdn
    - http://fontawesome.io/cheatsheet/
    - http://unicorn-ui.com/demo/svg.html
    - https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial/Basic_Shapes
    - http://www.clker.com/inc/svgedit/svg-editor.html
    - http://editor.method.ac/
    - http://realfavicongenerator.net/

---------------------------------------------------------------------------