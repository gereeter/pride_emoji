[Slack](https://slack.com) uses the [Noto Emoji](https://github.com/googlefonts/noto-emoji) set on all systems but macOS and ioOS and supports custom emoji as rasterized images up to 128x128.

## Notes

- The [pride flag](pride_flag.png) is provided for completeness despite being already available as `:rainbow_flag:`.
- Since there is no clear optimal custom emoji size (the builtin ones have multiple different sizes), images are rasterized to the maximum (128x128).
- Rasterization is done using the ImageMagick command `convert -backgroundd none -density 1536 -scane 128x128 google-noto/{}.svg slack/{}.png`.

## License

These images are simply rasterizations of the images provided in the [`google-noto`](../google-noto) directory; see the [README](../google-noto/README.md) there for license details.