[Discord](https://discordapp.com) uses the [Twemoji](https://twemoji.twitter.com) set rasterized to 32x32 images and supports custom emoji that are automatically resized to 32x32.

## Notes

- The [pride flag](pride_flag.png) is provided for completeness despite being already available as `:rainbow_flag:` or `:gay_pride_flag:`.
- Rasterization is done using the ImageMagick command `convert -background none -density 1364 -scale 32x32 twitter-twemoji/{}.svg discord/{}.png`.

## License

These images are simply rasterizations of the images provided in the [`twitter-twemoji`](../twitter-twemoji) directory; see the [README](../twitter-twemoji/README.md) there for license details.
