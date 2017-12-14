# redirector-rules
My redirect rules for [Redirector](https://chrome.google.com/webstore/detail/redirector/pajiegeliagebegjdhebejdlknciafen).

| From                                            | To                                 |
| ----------------------------------------------- | ---------------------------------- |
| `^https?://(.*?)\.m\.wikipedia\.org/(.*)`       | `https://$1.wikipedia.org/$2`      |
| `^https?://mobile\.twitter\.com/(.*)`           | `https://twitter.com/$1`           |
| `^https?://amp\.reddit\.com/(.*)`               | `https://reddit.com/$1`            |
| `^https?://www\.quora\.com/(.*?)(\|\?share=1)$` | `https://www.quora.com/$1?share=1` |
