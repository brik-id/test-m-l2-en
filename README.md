# Klontong, the Mobile Project

A small convenience store wants to enter the 21st century by selling their products online.

### Details

**Basic Overview:**

> As the child of the convenience store owner, I need to manage the products we sell in a table format.

From an engineer's perspective, consider this as just a CRUD application.

Your backend colleagues will prepare a RESTful API, but they are delayed. However, you still need to demonstrate features while the API is being developed. Your team has decided that the API will be mocked up first. As a highly skilled mobile developer, this responsibility falls on you.

Here is the mobile stack you **_must_** use for this project:

- Flutter
- Bloc/Provider/Cubit

_Hint_: There’s an automatic online CRUD backend: <br/>
[https://crudcrud.com/](https://crudcrud.com/)

### More Technical Details

The entire team has agreed on some specifications and technical limitations:

- All request and response payloads are in JSON format.
- There is a data schema.
- There are about 100 products that need to be managed, so use pagination techniques.
- The designated pages:
  - List all products with search and pagination features
  - Product details
  - Add a product
- State persistence. If you need to save a token (for authentication), make sure it’s stored securely.

Example schema:

```json
{
  "id": 86,
  "CategoryId": 14,
  "categoryName": "Cemilan",
  "sku": "MHZVTK",
  "name": "Ciki ciki",
  "description": "Ciki ciki yang super enak, hanya di toko klontong kami",
  "weight": 500,
  "width": 5,
  "length": 5,
  "height": 5,
  "image": "https://cf.shopee.co.id/file/7cb930d1bd183a435f4fb3e5cc4a896b",
  "harga": 30000
}
```

Don't forget, your team is international, so do your best to work in English.

### Extra features

Your team doesn’t expect these, but it would be nice to see:

- Error reporting. Sometimes we don’t know what issues are happening on different phone models. How can we get this data?
- TDD (Test-Driven Development), to give you confidence that all the code you write is well-tested.
- Applying SOLID principles.

KISS (Keep It Stupid Simple) - Don’t forget, your target audience might not be tech-savvy.

### What we care about

Use whatever libraries you are familiar with as if this were a real production app. Code design and cleanliness are more important than choosing the "right" library. Always strive to use best practices!

### Important!!
If you use environment variables, don’t forget to share them with us along with any credentials we might need.

### Closing

Don’t forget to set your GitHub repo to public and share it with us.

Happy coding!

Please submit your finished test to [bit.ly/4cWYsiX](https://bit.ly/4cWYsiX)
