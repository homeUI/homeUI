# HomeUI
This repo holds all information about the webapp "homeUI", which is an browser-based application to manage all services from your home-network or homeserver(s).

## Storage
The Items and Settings are stored in a json file with the following structure:
```
{
    "settings": {
        "theme": ""
    },
    "rows": [{
        "row_name": "",
        "items": [{
            "image": "",
            "title": "",
            "link": ""
        }, {
            "image": "",
            "title": "",
            "link": ""
        }, {
            "image": "",
            "title": "",
            "link": ""
        }]
    }]
}
```