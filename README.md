# Upgrade contracts using transparent proxy

Testing with brownie to perform the following:

1. Deploy basic contract
2. Deploy proxy admin contract
3. Deploy proxy contract with implementation pointing to basic contract in 1.
4. Deploy 2nd basic contract with added method not present in contract 1.
5. Upgrade using proxy to set implementation contract to contract in 4.
