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

## Related API's
If you are building a dApp, a website or a game using WAX Creator, you can make use of other WAX Services to power up your application:
 - [OAuth Implementation](https://docs.opskins.com/public/en.html#oauth) - Allows you to add a 'Login via WAX' button in your application and interact with the user's account using WAX Trade and OPSkins API's.
 - [WAX Trade API](https://github.com/OPSkins/trade-opskins-api) - May be used to retrieve user's inventory, manage trade offers, see meta-data of WAX NFT's, and much more. *Important*: to retrieve unique item data (like random attributes), you must use WAX Trade v2 endpoints.
 - [OPSkins API](https://docs.opskins.com/public/en.html#opskins-api-v2) - May be used to purchase or sell items on OPSkins, check lowest prices of items, handle cashouts, and much more.
