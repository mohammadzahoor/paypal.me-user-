# paypal.me-user-
curl -v -X GET https://api-m.sandbox.paypal.com/v1/identity/oauth2/userinfo?schema=paypalv1.1 \ -H "Content-Type: application/json" \ -H "Authorization: Bearer &lt;Access-Token>"
{
  "user_id": "https://www.paypal.com/webapps/auth/identity/user/mWq6_1sU85v5EG9yHdPxJRrhGHrnMJ-1PQKtX6pcsmA",
  "name": "identity test",
  "given_name": "identity",
  "family_name": "test",
  "payer_id": "WDJJHEBZ4X2LY",
  "address": {
    "street_address": "1 Main St",
    "locality": "San Jose",
    "region": "CA",
    "postal_code": "95131",
    "country": "US"
  },
  "verified_account": true,
  "emails": [
    {
      "value": "user1@paypal.com",
      "primary": true
    }
  ]
}
