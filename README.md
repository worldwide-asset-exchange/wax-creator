# API Documentation for [WAX Creator](https://creator.wax.io) Documentation

## API Interfaces
* [IItemSubmission](https://github.com/worldwide-asset-exchange/item-creation-management/blob/master/IItemSubmission.md) - This API Interface is from a shared WAX Service called ICM (Item Creation Management)

## API Response
A typical response may look like this:
```json
{
  "success":true,
  "message":"Your request was received."
}
```

A typical error response may look like this:
```json
{
  "success":false,
  "error":"The amount must be an integer."
}
```

## API Key
Steps to get an API Key:
 - Visit [WAX All Access](https://all-access.wax.io/account/security) and make sure you have 2FA enabled for your account.
 - Login into [WAX Creator](https://creator.wax.io) with your WAX All Access account.
 - Visit the [User Account](https://creator.wax.io/user) page on WAX Creator to generate or revoke your API Key.
 - Keep your API Key safe and never share it with anyone!
