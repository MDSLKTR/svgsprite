## svg sprite

- insert all svgs as symbols inside the svg tag with the sprite class
- then you can use these symbols anywhere with `<use xlink:href="ID"></use>` but you need to put `<use>` into an svg tag too
- so everything is inlined and therefore no requests issued
- and you can style the svgs with your css as you like :)
