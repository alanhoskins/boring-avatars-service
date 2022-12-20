## How to use Boring Avatars service

To generate a custom avatar just embed the following URL `https://source.boringavatar.com/` and append a variant, size and a username to generate a custom avatar.

### Variants
You can use one of the variants `marble`, `beam`, `pixel`, `sunset`, `ring` or `bauhaus`.

```
https://source.boringavatar.com/beam
```

![Avatar using marble variant](https://source.boringavatar.com/beam)

### Custom size

```
https://source.boringavatar.com/marble/40

```

![Avatar of 120px](https://source.boringavatar.com/marble/40)


```
https://source.boringavatar.com/marble/160

```

![Avatar of 120px](https://source.boringavatar.com/marble/120)


### Custom colors
You can pass an array of colors using the parameter `color`

```
https://source.boringavatar.com/marble/120/Maria%20Mitchell?colors=264653,2a9d8f,e9c46a,f4a261,e76f51
```
![Avatar for Maria Mitchell](https://source.boringavatar.com/marble/120/Maria%20Mitchell?colors=264653,2a9d8f,e9c46a,f4a261,e76f51)

### Square avatars
Use the parameter `square` to get square-shaped avatars.

```
https://source.boringavatar.com/marble/120/Maria%20Mitchell?square
```
![Square avatar for Maria Mitchell](https://source.boringavatar.com/marble/120/Maria%20Mitchell?square)


### Name

You can use a `username`, `email` or any random text to generate a unique `avatar`.


```
https://source.boringavatar.com/marble/120/Maria%20Mitchell
```
![Avatar for Maria Mitchell](https://source.boringavatar.com/marble/120/Maria%20Mitchell)


### Random avatar
If you just want to use random avatars without providing usernames, you can use the root endpoint. You will receive an `svg` image with a 80*80px size using the `marble` variant.

```
https://source.boringavatar.com/
```

![Random avatar](https://source.boringavatar.com/)
