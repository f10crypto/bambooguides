
# Integration Guide

[GitHub](https://github.com/bamboo-crypto/bamboo/)

The node software offers an api available on port 3000 (standard configuration)


## Setting up a Node
please follow the [Node Setup Guide](https://github.com/f10crypto/bambooguides/blob/main/node-setup-guide.md)

## Important Endpoints

[This list](https://github.com/bamboo-crypto/bamboo/blob/master/API.md) should cover all endpoints you need. 

## Transactions

Transactions look like this

<pre><code>{
  "amount": 1,
  "fee": 1,
  "from": "004AE69674A9747B462D348DB7188EF284A1157641335B2D1B",
  "signature": "CF96C47A81A77CCC4916BD5BBD31FB1229988459A63FAC66B7E9463A17FFC0C88C607BB6F7979E7B1D60B19764BED229684521CEB3DC5E334FB7C8663E49C00F",
  "signingKey": "3B870B3692B0FC4A93C0067189719D7941263E7F39738111E6D7B87CFC1FDF3A",
  "timestamp": "0",
  "to": "006FD6A3E7EE4B6F6556502224E6C1FC7232BD449314E7A124"
}</code></pre>
  
they are created through the `/create_transaction` endpoint and can be submitted to the `/add_transaction_json` endpoint

**(Note: multiple transactions with the same amount, fee, sender and recipient need to have a different timestamp/nonce or they will be rejected by the node)**


## Getting Help
In case you have any further questions feel free to join our Discord and/or contact me (f10#7898) directly.

