docker-compose up -d

docker-compose down

================================================================

bitcoin-cli getpeerinfo

bitcoin-cli addnode "testnet-seed.bitcoin.jonasschnelli.ch" "add"

================================================================

lncli --network=testnet getinfo

lncli --network=testnet listpeers

lncli --network=testnet connect 03fea840ee807cc68ee2359669d3f00b638ba521a8f269a6ad7e618776af55010f@18.158.93.160:9735
lncli --network=testnet connect 03781444afe27babf724304c25370f195d9d955065d7894539ed7db5fe596badb8@138.197.57.50:19735