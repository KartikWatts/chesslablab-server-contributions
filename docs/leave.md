# /leave

## Description

Allows to leave a game.

## Parameters

| Name | Description | Required |
| ---- | ----------- | -------- |
| `action` | `accept` | Yes |

## Usage

### Example

```js
ws.send('/leave accept');
```

```text
{
  "/leave": {
    "action": "accept"
   }
}
```
