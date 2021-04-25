Testing blockchain

#Testing transaction Endpoints

1. POST newNodeUrl for every Node for /register-and-broadcast-node endpoint to synchronize whole network, ex.({newNodeUrl: "http:/localhost:3001"}), ({newNodeUrl: "http:/localhost:3002"})
2. POST new transaction for /transaction/broadcast endpoint. For example ({"amount": 100, "sender": "S1212S", "recipent": "S32112S21"})

#Register transaction

1. POST to /transaction/broadcast endpoint JSON data ex. ({"amount": "100", "sender": "S21S", "recipient": "12E21"})

#Mine new block  

1. Use /mine in one of your blockchain