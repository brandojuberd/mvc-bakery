# Marketplace

Buatlah suatu aplikasi yang menyimpan data-data marketplace beserta productnya  

```
  Marketplace
    node app.js <command>

    commands: 
      node app.js help
      node app.js stores
      node app.js addStore <storeName> <storeAddress>
      node app.js addProduct <storeId> <productName> <productPrice> <stock>
```
=================================================
## JSON example
```
[
  {
    "name" : "Game Store"
    "address": "Jakarta"
    "products": [
      [Product],
      [Product]
    ]
  }
]
```
