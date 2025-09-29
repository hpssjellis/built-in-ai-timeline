# built-in-ai-timeline
Timeline data visualization using the Chrome built in AI


The Demo is at   https://hpssjellis.github.io/built-in-ai-timeline/index.html










Prompt example:


Generate a list of 8 to 10 major military campaigns, treaties, and political events related to Napoleon Bonaparte's conquest and reign in Europe, spanning from 1799 to 1815. For each event, provide a precise date and a brief, descriptive title.

Adhere to the following JSON schema:
[
  {
    "id": "A unique string ID, like a timestamp",
    "date": "An ISO 8601 string, e.g., YYYY-MM-DDTHH:MM:SS.sssZ",
    "description": "A concise description of the event"
  }
]




.


.

.

.


better prompt for range

Generate a list of 8 to 10 significant events related to wwII.  For some events, provide both a start and an end date to represent a range.

Adhere strictly to the following JSON schema array: [ { "id": "A unique string ID, like a timestamp", "date": "The event start date as an ISO 8601 string (YYYY-MM-DDTHH:MM:SS.sssZ)", "end": "The event end date as an ISO 8601 string (YYYY-MM-DDTHH:MM:SS.sssZ). This property is optional. Use it for range events like wars or projects.", "description": "A concise, descriptive title for the event or range." } ]
