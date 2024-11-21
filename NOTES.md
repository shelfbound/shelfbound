# Google API Fieldmasks

I want to store the whole string in a variable in Postman.
It's easier to type it out here and then paste into a variable.

## fieldmasks for book search results

**items.volumeInfo** -

- `items` is the object containing the items/volumes from the search results.
- `volumeInfo` is the object for each item that contains all the info I want in the search results.
- this prefixes all deeper fields

items.volumeInfo.title,items.volumeInfo.subtitle,items.volumeInfo.authors,items.volumeInfo.publisher,items.volumeInfo.publishedDate,items.volumeInfo.description,items.volumeInfo.industryIdentifiers.type,items.volumeInfo.industryIdentifiers.identifier,items.volumeInfo.categories,items.volumeInfo.imageLinks.smallThumbnail,items.volumeInfo.imageLinks.thumbnail,items.volumeInfo.previewLink

# auth0 user object

## Example using cregmitn user

```js
{
  "created_at": "2024-10-29T20:00:28.093Z",
  "email": "cregmitn@gmail.com",
  "email_verified": true,
  "identities": [
      {
          "connection": "Username-Password-Authentication",
          "provider": "auth0",
          "user_id": "67213edc1a769e4773c5e2ba",
          "isSocial": false
      }
  ],
  "name": "cregmitn@gmail.com",
  "nickname": "cregmitn",
  "picture": "https://s.gravatar.com/avatar/c8cfa0ebea99e299c2cf807ba8924f12?s=480&r=pg&d=https%3A%2F%2Fcdn.auth0.com%2Favatars%2Fcr.png",
  "updated_at": "2024-11-18T23:58:33.934Z",
  "user_id": "auth0|67213edc1a769e4773c5e2ba",
  "last_ip": "24.252.68.31",
  "last_login": "2024-11-18T23:58:33.934Z",
  "logins_count": 23,
  "blocked_for": [],
  "guardian_authenticators": [],
  "passkeys": []
}
```