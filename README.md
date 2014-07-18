jQuery Loader Fullscreen
=====================

jQuery Loader Fullscreen

This plugin is very simple to configure in your site.
Create a div like this

`<div class="overlay"></div>`

after the body tag.

Include javascript and css reference:


`<link href="jquery.loader.fullscreen.css" rel="stylesheet">`  
`<script src="jquery.loader.fullscreen.js"></script>`

Finally, you can call the loader.begin()

      <script>
            $(document).ready(function(){
                $('#showloader').click(function() {
             
                    loader.begin();
                    
                    setTimeout(function(){
                        loader.stop();
                    }, 3000); 
                });
            });
        </script>
