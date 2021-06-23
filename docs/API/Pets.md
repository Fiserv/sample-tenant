# Pets
![Friends]

[//]: #
[Friends]: <https://github.com/Fiserv/sample/blob/develop/assets/images/friends-1149841_1920.jpg>

## Overview
- Description:
    - Quickly add, update, find, or delete your pets. You can manage all of your pets using this feature as well as upload pictures.
- Tags:
    - "pets", "api"
- Bullets:
    - "Increase payment security and reduce risk", "No need to store personal customer information", "Less operational costs", "Improved customer experience"
- Links:
    - "docs/Resources/API-Documents/Payments_VAS/Payment-Token.md"

## Featured APIs
  - Add Pet
    - Description: Add a pet to the inventory.
    - Type: POST
    - Path: /pet
    - Language: Curl
    - Link: link to API Explorer
    - Code Sample:
        -       '[json {
                "id": 0,
                    "category": {
                      "id": 0,
                      "name": "string"
                    },
                    "name": "doggie",
                    "photoUrls": [
                      "string"
                    ],
                    "tags": [
                      {
                        "id": 0,
                        "name": "string"
                      }
                    ],
                    "status": "available"
                  }
                ]'
  - Update Pet
    - Description: Updates a pet in the inventory.
    - Type: PUT
    - Path: /pet
    - Language: Curl
    - Link: link to API Explorer
    - Code Sample:
        -       '[json
                   {
                    "id": 0,
                    "category": {
                      "id": 0,
                      "name": "string"
                    },
                    "name": "doggie",
                    "photoUrls": [
                      "string"
                    ],
                    "tags": [
                      {
                        "id": 0,
                        "name": "string"
                      }
                    ],
                    "status": "available"
                    }
                  ]'

## Use Case
  - Find the Perfect Pet
    - Subtitle: Pets
    - Description:  
      - Customers can find their new best friend by checking which pets are available and browsing through pet images. 
      - Shopkeepers can easily update an existing pet's data by finding that pet's petId and add and delete pets to reflect their inventory.
      

## Related Links
- [Store.md](?path=docs/API/Store.md)
- [User.md](?path=docs/API/Pets.md)
