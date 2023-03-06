Used for get list user transactions

**Data**

| Name | Type | Required | Description |
| --- | --- | --- | --- |
| page | int | optional | must be >= 0 |
| size | int | optional | must be > 0 and <= 20 |
| from_time | int64 | optional |  |
| to_time | int64 | optional |  |

**Error code**

| Status Code | Title | Description |
| --- | --- | --- |
| 400 | INVALID_DATA | Bad request, please check and try again. |

Field \`status\` just exist if transaction is WITHDRAWAL or WITHDRAWAL_COD

Values: PENDING, CANCELLED, TRANSFERRED, PROCESSING
