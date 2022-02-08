# Brascoin
Crypto coin code 
Welcome to the Brascoin Crypto Coin Example

Here you can simulate a execution of crypto currency based on a blockchain.
For to do that, execute each file separately.
Each one will be a node instance.
You can execute the following actions:

mine_block - GET
get_chain - GET
is_valid - GET
add_transaction - POST - As JSON example:
{
    "sender": "",
    "receiver": "",
    "amount":   1
}

connect_node - POST - As JSON example (Just list the othe nodes):
{
    "nodes": ["http://127.0.0.1:5001", 
              "http://127.0.0.1:5002", 
              "http://127.0.0.1:5003"]
}

replace_chain - GET


Thanks for Fernando Amaral e Ligency I Team
