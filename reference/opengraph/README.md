# OpenGraph

1200×630 files to be used as opengraph images.

## HTML Example:

```html
<meta name="twitter:image" content="{{ site.url }}{{ site.baseurl }}/images/opengraph-pogodev.png" />

<meta property="og:image" content="{{ site.url }}{{ site.baseurl }}/images/opengraph-pogodev.png" />
<meta property="og:image:width" content="1200" />
<meta property="og:image:height" content="630" />
```

### Notes

* the `pngs` are willingly not optimized as some sites tend to resize them on their own and make them look crappy.
* Don't forget to add the other `og` or `twitter` meta data.
* Replace the [Liquid](https://shopify.github.io/liquid/) stuff (`{{ }}` and `{% %}`) if not in Jekyll
