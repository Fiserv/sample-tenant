# Pets
## Overview
- Description:
      Quickly add, update, find, or delete your pets. You can manage all of your pets using this feature as well as upload pictures.
    tags: ["pets", "api"]
    bullets: ["Increase payment security and reduce risk", "No need to store personal customer information", "Less operational costs", "Improved customer experience"]
    links: ["docs/Resources/API-Documents/Payments_VAS/Payment-Token.md"]
  - title: Store
    description: >
      Place, find, or delete orders at your store. You can manage inventory and keep track of your store.
    tags: ["store", "api"]
    bullets: ["Faster acceptance than credit or debit", "Biometric security", "Global offering and acceptance"]
    links: ["docs/Online-Mobile-Digital/Wallets-AltPayments/Apple-Pay/Apple-Pay.md"]
  - title: User
    description: >
      You are also able to create, get, update, or delete your users. You are also able to log-in and log-out a user.
    tags: ["user", "api"]
    bullets: ["Modern technology stack", "Automated backoffice", "Fast testing, certification and implementation"]
    links: ["docs/Resources/API-Documents/Use-Our-APIs.md"]
    
    featuredAPIs:
  - name: Add Pet
    description: Used to add a pet.
    type: post
    path: /pet
    codeSample: '[json
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
    
- Link to other thingies
- Api explorer
