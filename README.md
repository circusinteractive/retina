retina
======

Fix para optimizar la resolución de imágenes en dispositvos con retina display

Ejemplo:
--------

Will compile to: 

#logo {
  background-image: url('/images/my_image.png');
}

@media all and (-webkit-min-device-pixel-ratio: 1.5) {
  #logo {
    background-image: url('/images/my_image@2x.png');
    background-size: 200px 100px;
  }
}
