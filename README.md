# bet365-chrome-extension
Chrome extension to extract odds and bet information of Bet365's site

Match
=====

```json

"match": {
    "home": "FBC Melgar", 
    "away": "Unión Comercio",
    "time": "34:05",
    "score": "1:0",
    "stats": {
        "attacks": "37:54",
        "dangerousAttacks": "9:29",
        "possesion": "45:54",
        "corners": "2:4",
        "redCards": "0:0",
        "yellowCards": "2:1",
        "shotsOnTarget": "1:2",
        "shotsOffTarget": "2:4"
    }
}

```

Match Event
===========

```json
"matchEvent": {
    "time": "61:45",
    "team": "FBC Melgar",
    "player": "Ruben",
    "eventType": "Attack",
    "ballCoordLeft": "240px",
    "ballCoordTop": "80px"
}
```

Available Bet Options
======================

```json
"availableBets": [
    {
        "title": "Match Goals",
        "options": [
            {
                "header":
                "odds": [
                    {
                        "name":"",
                        "odd":""
                    }
                ]
            },
            {
                "odds": [
                    {
                        "name":"",
                        "odd":""
                    }
                ]
            }
        ]
    }
]

```