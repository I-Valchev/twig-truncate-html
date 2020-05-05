# Installation

```
composer require ivovalchev/twig-truncate-html
```

And add it to your `services.yaml`:
```
    app.twig_extension:
        class: IvoValchev\TruncateHtmlExtension\TruncateHtmlExtension
        tags:
            - { name: twig.extension }

```

# How to use

```
{{ "<p>hello world</p>"|truncate_html(5) }}
```
