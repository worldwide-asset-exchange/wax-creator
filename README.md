# API Documentation for [WAX Creator Documentation](https://creator.wax.io)

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