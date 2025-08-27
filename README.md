# Lakshya Backend (Azure Functions + Cosmos DB)

This backend handles pledge submissions for Lakshya using Azure Functions and Cosmos DB.

## API Endpoint

**POST** `/api/submitPledge`

### Request Body
```json
{
  "name": "Sushali",
  "email": "sushali@example.com",
  "message": "I pledge to support civic tech!"
}
