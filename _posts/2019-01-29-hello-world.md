---
title: "Welcome to Jekyll!"
published: true
---

**Hello world**, this is my first Jekyll blog post.

I hope you like it!

# Highlighter
## Ruby
```ruby
def show
  puts "Outputting a very lo-o-o-o-o-o-o-o-o-o-o-o-o-o-o-o-ong lo-o-o-o-o-o-o-o-o-o-o-o-o-o-o-o-ong line"
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
```

## Php
```php
<?php
  print("Hello {$world}");
?>
```

## Java
```java
public class java {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
```

## HTML
```html
<html>
  <head><title>Title!</title></head>
  <body>
    <p id="foo">Hello, World!</p>
    <script type="text/javascript">var a = 1;</script>
    <style type="text/css">#foo { font-weight: bold; }</style>
  </body>
</html>
```

## Console
```console
# prints "hello, world" to the screen
~# echo Hello, World
Hello, World

# don't run this
~# rm -rf --no-preserve-root /
```

## Css
```css
body {
    font-size: 12pt;
    background: #fff url(temp.png) top left no-repeat;
}
```

## Yaml
```yaml
---
one: Mark McGwire
two: Sammy Sosa
three: Ken Griffey
```
<div id="graphcomment"></div>
<script type="text/javascript">

  /* - - - CONFIGURATION VARIABLES - - - */

  // make sure the id is yours
  window.gc_params = {
    graphcomment_id: 'ac0rdsoftware',

    // if your website has a fixed header, indicate it's height in pixels
    fixed_header_height: 0,
  };

  /* - - - DON'T EDIT BELOW THIS LINE - - - */

  
  (function() {
    var gc = document.createElement('script'); gc.type = 'text/javascript'; gc.async = true;
    gc.src = 'https://graphcomment.com/js/integration.js?' + Math.round(Math.random() * 1e8);
    (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(gc);
  })();

</script>
