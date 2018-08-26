{
  "info": {
    "name": "Yapily Retrieves details of a specific institution available in Yapily",
    "_postman_id": "e273b561-cbdd-45e4-afcb-8b37d56af3a4",
    "description": "Retrieves details of a specific institution available in yapily.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Accounts",
      "item": [
        {
          "id": "df1b883e-4ffc-4da0-8c16-4a9d8c2782de",
          "name": "getAccountsUsingGET",
          "request": {
            "url": "http://api.yapily.com:443/accounts",
            "method": "GET",
            "header": [
              {
                "key": "consent",
                "value": "{}",
                "description": "Consent Token",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get accounts."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "955a66dd-15a3-46e5-939e-7cd5b13a7468"
            }
          ]
        }
      ]
    },
    {
      "name": "Account",
      "item": [
        {
          "id": "8aba6850-c406-4bb3-a0f7-39722b17056c",
          "name": "getAccountUsingGET",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.yapily.com",
              "path": [
                "accounts/:accountId"
              ],
              "port": "443",
              "variable": [
                {
                  "id": "accountId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "consent",
                "value": "{}",
                "description": "Consent Token",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cada76c6-87b7-41c6-a7cd-387d338995e9"
            }
          ]
        },
        {
          "id": "283bd377-66d8-4c10-8141-0b70f3024b65",
          "name": "getTransactionsUsingGET",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.yapily.com",
              "path": [
                "accounts/:accountId/transactions"
              ],
              "port": "443",
              "variable": [
                {
                  "id": "accountId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "consent",
                "value": "{}",
                "description": "Consent Token",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get account transactions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1666557d-4138-428d-b6d9-d882b668c7b4"
            }
          ]
        }
      ]
    },
    {
      "name": "Identity",
      "item": [
        {
          "id": "7d625f1b-b74a-429f-9d9d-2dc81c399030",
          "name": "identityUsingGET",
          "request": {
            "url": "http://api.yapily.com:443/identity",
            "method": "GET",
            "header": [
              {
                "key": "consent",
                "value": "{}",
                "description": "Consent Token",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get identity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e5d9b287-2e9c-4e5a-b705-1302bb73ddef"
            }
          ]
        }
      ]
    },
    {
      "name": "Retrieves",
      "item": [
        {
          "id": "96e4806d-f443-4880-acbf-c4b95d0f16c5",
          "name": "getInstitutionsUsingGET",
          "request": {
            "url": "http://api.yapily.com:443/institutions",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the list of institutions available in yapily."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f7852bef-5f71-4713-9237-9d3bd97e0b9e"
            }
          ]
        },
        {
          "id": "00eaaff0-0556-4c4e-94a9-77454da892db",
          "name": "getInstitutionUsingGET",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.yapily.com",
              "path": [
                "institutions/:institutionId"
              ],
              "port": "443",
              "variable": [
                {
                  "id": "institutionId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves details of a specific institution available in yapily."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f7c8e2f2-e406-409a-9153-e85b9c952b9c"
            }
          ]
        }
      ]
    }
  ]
}