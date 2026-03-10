# Joke Microservice
Want a funny programming joke? Simply call this API with no parameters and get a funny joke!

## Example Call:
POST http://localhost:5539/ HTTP/1.1
content-type: application/json

{
}

```json
{
  "error": false,
  "category": "Programming",
  "type": "twopart",
  "setup": "What do you call a developer who doesn't comment code?",
  "delivery": "A developer.",
  "flags": {
    "nsfw": false,
    "religious": false,
    "political": false,
    "racist": false,
    "sexist": false,
    "explicit": false
  },
  "id": 14,
  "safe": true,
  "lang": "en"
}
```