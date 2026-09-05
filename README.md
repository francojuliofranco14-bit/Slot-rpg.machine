wc -l slots-julio.html; sed -n '520,540p' slots-julio.html1057 slots-julio.html
  <div id="win-flash">
    <...{
  "action": "create",
  "entity_name": "SlotsOrder",
  "schema": {
    "properties": {
      "amount": {
        "type": "number"
      },
      "currency": {
        "type": "string"
      },
      "order_id": {
        "type": "string"
      },
      "payer_email": {
        "type": "string"
      },
      "status": {
        "type": "string",
        "enum": [
          "paid",
          "pending",
          "refunded"
        ]
      },
      "txn_id": {
        "type": "string"
      }
    },
    "type": "object"
  }
}
