# Store
![Store]

[//]: #
[Store]: <https://github.com/Fiserv/sample/blob/develop/assets/images/cat-840260_1920.jpg>

## Overview
- Description:
    -  Place, find, or delete orders at your store. You can manage inventory and keep track of your store.
- Tags:
    - "store"
    - "api"
- Bullets:
    - "Faster acceptance than credit or debit"
    - "Biometric security"
    - "Global offering and acceptance"
- Links:
    - "docs/Online-Mobile-Digital/Wallets-AltPayments/Apple-Pay/Apple-Pay.md"
    

## Featured APIs
  - Place Order
    - Description: Places order for a pet.
    - Type: POST
    - Path: /store/order
    - Language: Curl
    - Link: link to API Explorer
    - Code Sample:
        -       '[json
                  {
                    "id": 0,
                    "petId": 0,
                    "quantity": 0,
                    "shipDate": "2021-06-21T21:55:37.319Z",
                    "status": "placed",
                    "complete": true
                   }
                  ]'
  - Find Order
    - Description: Find purchase order by ID.
    - Type: GET
    - Path: /store/order/{orderID}
    - Language: Curl
    - Link: link to API Explorer
    - Code Sample:
        -       '[json
                  {
                    "id": 0,
                    "petId": 0,
                    "quantity": 0,
                    "shipDate": "2021-06-21T21:57:19.714Z",
                    "status": "placed",
                    "complete": true
                  }
                  ]'

## Use Case
  - Effective and Effcient Inventory Management 
    - Subtitle: Store
    - Description:  
      - Shopkeepers are treated with an innovative petkeeping system that tracks orders with their respective orderIDs and can retrive shopkeepers' pet inventory by status with ease.
      

## Related Links
- [Pets.md](?path=docs/API/Pets.md)
- [User.md](?path=docs/API/User.md)
