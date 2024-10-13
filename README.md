Sources used:
- https://quotes.toscrape.com/js (JS loads all data, pagination)
- https://quotes.toscrape.com/ (static, pagination)
- https://quotes.toscrape.com/scroll (infinite scrolling with JS)

There are 100 quotes total. The above links only differ by how the data (quotes) are loaded.

The results, regardless of the method used for scraping should be saved as a JSON file, containing all 100 quotes:

```json
[
    {
        "quote": "\u201cThe world as we have created it is a process of our thinking. It cannot be changed without changing our thinking.\u201d",
        "by": "Albert Einstein",
        "tags": [
            "change",
            "deep-thoughts",
            "thinking",
            "world"
        ]
    },

    {
        "quote": "\u201cThere are only two ways to live your life. One is as though nothing is a miracle. The other is as though everything is a miracle.\u201d",
        "by": "Albert Einstein",
        "tags": [
            "inspirational",
            "life",
            "live",
            "miracle",
            "miracles"
        ]
    },
    ...
   {
        "quote": "\u201c... a mind needs books as a sword needs a whetstone, if it is to keep its edge.\u201d",
        "by": "George R.R. Martin",
        "tags": [
            "books",
            "mind"
        ]
    }
]
```