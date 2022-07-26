# json_emoji
A simple JSON file for adding whatsapp-like emoji to your document

# Warning!
## The file is very large in size. It is about 3 MB!

JSON Emoji contains over 1,000 list of properly organized emoji.\
The various emoji are grouped into 50 categories which includes:
  
- Face
- Emotion
- Hand
- Body
- Person
- Family
- Animal
- Plant
- Food
- Drink
- Dishware
- Place
- Transport
- Hotel
- Time
- Sky Weather
- Event
- Award
- Sport
- Game
- Arts Crafts
- Clothing
- Sound
- Music
- Phone
- Computer
- Light Video
- Book
- Money
- Mail
- Writing
- Office
- Lock
- Tool
- Science
- Medical
- Household
- Other
- Warning
- Arrow
- Religion
- Zodiac
- Symbol
- Math
- Punctuation
- Currency
- Keycap
- Alphanum
- Geometric
- Flag

Each category contains a list of object.\
The object contains emoji the emoji in different format which includes image, hex, dec and HTML entity.

#### Like the example below

```json
  {
    "face": [
        {
          "name":"face with tears of joy",
          "hex":"1F602",
          "dec":"128514",
          "icon":"😂",
          "img":"data:image/png;base64,..."
        },
        "..."
    ],
    "emotion": [
        {
          "name":"kiss mark",
          "hex":"1F48B",
          "dec":"128139",
          "icon":"💋",
          "img":"data:image/png;base64,..."
        },
        "..."
    ],
    "..."
  }
```
