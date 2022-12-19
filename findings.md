fetch("https://moovitapp.com/api/lines/linearrival", {
  "headers": {
    "accept": "application/x-protobuf",
    "accept-language": "it-IT,it;q=0.9",
    "cache-control": "no-cache",
    "content-type": "application/json",
    "moovit_app_type": "WEB_TRIP_PLANNER",
    "moovit_client_version": "5.105.1/V567",
    "moovit_customer_id": "4908",
    "moovit_metro_id": "223",
    "moovit_phone_type": "2",
    "moovit_user_key": "F36562",
    "pragma": "no-cache",
    "protobuf-version": "V3",
    "rbzid": "IVgJnQRzu4jDt3yWwZJMOg/mfjU0jhCKrk7/65JE97gV3rCfgozF+ReZI+oTXgSGbbDescqAvP2J4zK0uqfsK0WNLgAs8TFpPJnzBQD1wUiCEN88+P6gASAddLTj1qeIZeEHZGOiCj6MThIi5KMkNRylsZXZZ4dKBkylWqihIbKcRMiqKlGmhFEGoi6BfHbWLGfaI4NdfwHfjwxY6dYzJT/2EyTng+kEXRDLOIROBeCGFcGME0wYeNSnNKiWhiod",
    "sec-ch-ua": "\"Not?A_Brand\";v=\"8\", \"Chromium\";v=\"108\", \"Google Chrome\";v=\"108\"",
    "sec-ch-ua-mobile": "?0",
    "sec-ch-ua-platform": "\"Windows\"",
    "sec-fetch-dest": "empty",
    "sec-fetch-mode": "cors",
    "sec-fetch-site": "same-origin"
  },
  "referrer": "https://moovitapp.com/milano_e_lombardia-223/lines/27/586850/1/it?ref=4&customerId=4908",
  "referrerPolicy": "strict-origin-when-cross-origin",
  "body": "{\"query\":\"ChF7ImlkcyI6WzM4MDYzODldfRCV15MC\"}", //base64 for
  "method": "POST",
  "mode": "cors",
  "credentials": "include"
});


"body": "{\"query\":\"ChF7ImlkcyI6WzM4MDYzODldfRCV15MC\"}", //base64 for

ChF7ImlkcyI6WzM4MDYzODldfRCV15MC
ChF7ImlkcyI6WzM4MDYzODldfR => {"ids":[3806389]}
CV15MC

CiF7ImlkcyI6WzM4MDY0NTcsMzgwNjQ1NiwzODA2NTAyXX0Q3PuSAQ==
CiF7ImlkcyI6WzM4MDY0NTcsMzgwNjQ1NiwzODA2NTAyXX0 => !{"ids":[3806457,3806456,3806502]}
Q3PuSAQ==

response translated to
e: array

[
    {
        "stopId": 4516757,
        "epochDay": 19345,
        "lineArrivals": {
            "arrivals": [
                {
                    "attributes": [],
                    "patternId": 8134756,
                    "tripId": 972786675,
                    "relativeStaticTimeSpanSeconds": 85729,
                    "relativeRealTimeSpanSeconds": 85745, //time of arrival in seconds after current day
                    "isLastArrival": false,
                    "durationInSeconds": 600,
                    "stopIndex": 5,
                    "patternStopsSize": 23
                }
            ],
            "shapeSegments": [],
            "lineId": 3806389
        }
    }
]

https://github.com/YuvalPruss/MoovitComputerAlerts/blob/master/moovit_crawler.py