{
  "info": {
    "name": "Yapily Retrieves the list of institutions available in Yapily",
    "_postman_id": "13dc12b9-6107-4a53-b572-d98e20c87a10",
    "description": "Retrieves the list of institutions available in yapily.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Accounts",
      "item": [
        {
          "id": "84ad0e20-b52b-47b0-aa74-01fa7fc6a01e",
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
              "id": "1f40d81b-e2ff-434e-aa32-2e8f6078ce8e"
            }
          ]
        }
      ]
    },
    {
      "name": "Account",
      "item": [
        {
          "id": "009d760f-b9dc-4bf2-aee8-d9a940216c1b",
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
              "id": "07deb76c-6411-42f5-87f1-54249d689b52"
            }
          ]
        },
        {
          "id": "e974694c-c40f-45b6-8470-7accd8388659",
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
              "id": "2ef22283-8119-4475-b7b0-669c90ccc897"
            }
          ]
        }
      ]
    },
    {
      "name": "Identity",
      "item": [
        {
          "id": "ca0499bd-1c2c-4442-9222-ea68cad64db8",
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
              "id": "e7b590b3-f782-4337-bc7d-ea2cafa036db"
            }
          ]
        }
      ]
    },
    {
      "name": "Retrieves",
      "item": [
        {
          "id": "3d72aa9c-40b8-4ebf-a921-d78c74503448",
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
              "id": "e1606631-043f-4e2b-8e2e-62ce16040080"
            }
          ]
        }
      ]
    }
  ]
}