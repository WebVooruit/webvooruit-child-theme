# webvooruit-child-theme
Basis Wordpress Child Theme

## andere css in eigen child gebruiken
```
wp_enqueue_style( 'custom-style', get_stylesheet_directory_uri().'/eigen-thema.css' );
```
Let hierbij op het verschil van de functie die gebruikt wordt om de directory te kiezen.
`get_stylesheet_directory_uri()` is de map van de active CSS (child theme)
`get_template_directory_uri()` is de map van het hoofdtheme wat hierbij hoort (theme / parent theme)
