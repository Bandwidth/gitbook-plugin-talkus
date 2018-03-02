# gitbook-plugin-talkus
Add [talkus](https://talkus.io) chat button to gitbook web pages

### How to use?

Add plugin to your `book.json`, then run `gitbook install`:

```json
{
    "plugins": ["talkus"]
}
```

#### Configure usabilla token:

![Configure](usabilla.png)

```json
{
    "plugins": ["talkus"],
    "pluginsConfig": {
        "talkus": {
            "talkusId": "12345678abc"
        }
    }
}
```

### Inspiration
Inspired by: https://github.com/chudaol/gitbook-plugin-gtm
