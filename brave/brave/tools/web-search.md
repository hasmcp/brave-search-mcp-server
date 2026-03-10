# webSearch

Performs a web search using Brave Search API.

## API Details

- **Method:** `GET`
- **Endpoint:** `https://api.search.brave.com/res/v1/web/search`

### Query Arguments

```json
{
  "properties": {
    "q": {
      "description": "Search terms (max 400 chars, 50 words)",
      "type": "string"
    }
  },
  "required": [
    "q"
  ],
  "type": "object"
}
```

## Required Variables

- `API_SEARCH_BRAVE_COM_API_KEY`

## Headers

- `X-Subscription-Token: ${API_SEARCH_BRAVE_COM_API_KEY}`
- `Accept: application/json`

