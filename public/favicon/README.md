# Fav Icons

Assets related to favicons and Safari / Apple Touch Icon / Android / MS tiles...

Here is what the `<head></head>` part should look like :

```html
<link href="{{ site.baseurl }}/images/apple-touch-icon.png" rel="apple-touch-icon" sizes="180x180" >
<link href="{{ site.baseurl }}/images/favicon-32x32.png" rel="icon" type="image/png" sizes="32x32" />
<link href="{{ site.baseurl }}/images/favicon-16x16.png" rel="icon" type="image/png" sizes="16x16" />
<link href="{{ site.baseurl }}/favicon.ico" type="image/x-icon" rel="icon"/>
<link href="{{ site.baseurl }}/favicon.ico" type="image/x-icon" rel="shortcut icon"/>
<link href="{{ site.baseurl }}/manifest.json" rel="manifest" >
<link href="{{ site.baseurl }}/images/safari-pinned-tab.svg" rel="mask-icon" color="#e95c5a" />
<meta content="{{ site.baseurl }}/browserconfig.xml" name="msapplication-config" />
<meta content="#131416" name="theme-color" />
```

## Notes:

* The `favicon.ico`, `manifest.json` and `browserconfig.xml` should be in the root folder.
* Don't forget to update the `browserconfig.xml` and the `manifest.json` files.
* Remove the [Liquid](https://shopify.github.io/liquid/) stuff (`{{ }}` and `{% %}`) and the [front matter](https://jekyllrb.com/docs/frontmatter/) if not in Jekyll (also in `browserconfig.xml` and `manifest.json`).
