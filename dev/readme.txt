Testing blockchain

#Testing transaction Endpoints
1. POST newNodeUrl for every Node for /register-and-broadcast-node endpoint, ex.({newNodeUrl: "http:/localhost:3001"}), ({newNodeUrl: "http:/localhost:3002"})
2. POST new transaction for /transaction/broadcast endpoint. For example ({"amount": 100, "sender": "S1212S", "recipent": "S32112S21"})