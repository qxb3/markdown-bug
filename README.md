# markdown-bug

Its weird that this html code turns into some code blocks <br>
Example Code:

```html
<ul>
  <li>
    connect(options) <br>
     - Connect the client <br>
     <ul>
       <li>
          lang (string) <br>
          Default: 'en'
       </li>

       <li>
          topics (Array&lt;String&gt;) <br>
          Default: []
       </li>

       <li>
          another one
       </li>
     </ul>
  </li>

  <li>
    another one (2) <br>
    
    This time its its in the nested list? :/
  </li>
</ul>
```

# Example

what you will see when you run it:

<ul>
  <li>
    connect(options) <br>
     - Connect the client <br>
     <ul>
       <li>
          lang (string) <br>
          Default: 'en'
       </li>

       <li>
          topics (Array&lt;String&gt;) <br>
          Default: []
       </li>

       <li>
          another one
       </li>
     </ul>
  </li>

  <li>
    another one (2) <br>
    
    This time its its in the nested list? :/
  </li>
</ul>
