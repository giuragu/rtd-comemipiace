# Prova pagina 1

## 1 paragrafo

### 2 paragrafo

## Footenotes

per vedere[^1] come viene il footenotes[^2]

[^1]: Lorem ipsum dolor sit amet, consectetur adipiscing elit.

[^2]: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod ulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.


   
`codice`

   
> questo per "`evidenziare`"
   ```  
       *uno*
       due tre 
       quattro
       cinque
   ```

---
   
## Content tabs
   
=== "A"

    ``` A
    uno due tre
    bla bla
    ```

=== "B"

    ``` B
    quattro cinque sei

    bla bla bla
    ```

   
## Embedded content
   
!!! example

    === "Unordered List"

        _Example_:

        ``` markdown
        * Sed sagittis eleifend rutrum
        * Donec vitae suscipit est
        * Nulla tempor lobortis orci
        ```

        _Result_:

        * Sed sagittis eleifend rutrum
        * Donec vitae suscipit est
        * Nulla tempor lobortis orci

    === "Ordered List"

        _Example_:

        ``` markdown
        1. Sed sagittis eleifend rutrum
        2. Donec vitae suscipit est
        3. Nulla tempor lobortis orci
        ```

        _Result_:

        1. Sed sagittis eleifend rutrum
        2. Donec vitae suscipit est
        3. Nulla tempor lobortis orci

   
---
   
---
   
## Disqus codice da editare sulla pagina .md
   
``` html
<script id="dsq-count-scr" src="//guida-readthedocs.disqus.com/count.js" async></script>
<div id="disqus_thread"></div>
<script>
var disqus_config = function () {
this.page.url = PAGE_URL;  
this.page.identifier = PAGE_IDENTIFIER; 
};
(function() { 
var d = document, s = d.createElement('script');
s.src = 'https://guida-readthedocs.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
```

   
<script id="dsq-count-scr" src="//guida-readthedocs.disqus.com/count.js" async></script>
<div id="disqus_thread"></div>
<script>
var disqus_config = function () {
this.page.url = PAGE_URL;  
this.page.identifier = PAGE_IDENTIFIER; 
};
(function() { 
var d = document, s = d.createElement('script');
s.src = 'https://guida-readthedocs.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>

   

