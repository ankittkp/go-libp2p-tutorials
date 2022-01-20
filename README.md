# go-libp2p-tutorials

libp2p is a modular system of protocols, specifications and libraries 
that enable the development of peer-to-peer network applications.

# Peer-to-peer basics
In peer-to-peer (P2P) networking, a group of computers are linked together with equal permissions and responsibilities for processing data. Unlike traditional client-server networking, no devices in a P2P network are designated solely to serve or to receive data. Each connected machine has the same rights as its “peers”, and can be used for the same purposes. Peers are both clients and servers at the same time.

# Uses of Peer-to-peer
P2P is used to share all kinds of computing resources such as processing power, network bandwidth, or disk storage space. However, the most common use case for peer-to-peer networks is the sharing of files on the internet. Peer-to-peer networks are ideal for file sharing because they allow the computers connected to them to receive files and send files simultaneously.


# listening-node
./libp2p-node
libp2p node address: /ip4/127.0.0.1/tcp/61790/ipfs/QmZKjsGJ6ukXVRXVEcExx9GhiyWoJC97onYpzBwCHPWqpL

# second-node which has the address of first node with some ping responses

./libp2p-node /ip4/127.0.0.1/tcp/61790/ipfs/QmZKjsGJ6ukXVRXVEcExx9GhiyWoJC97onYpzBwCHPWqpL
libp2p node address: /ip4/127.0.0.1/tcp/61846/ipfs/QmVyKLTLswap3VYbpBATsgNpi6JdwSwsZALPxEnEbEndup
sending 5 ping messages to /ip4/127.0.0.1/tcp/61790/ipfs/QmZKjsGJ6ukXVRXVEcExx9GhiyWoJC97onYpzBwCHPWqpL
pinged /ip4/127.0.0.1/tcp/61790/ipfs/QmZKjsGJ6ukXVRXVEcExx9GhiyWoJC97onYpzBwCHPWqpL in 431.231µs
pinged /ip4/127.0.0.1/tcp/61790/ipfs/QmZKjsGJ6ukXVRXVEcExx9GhiyWoJC97onYpzBwCHPWqpL in 164.94µs
pinged /ip4/127.0.0.1/tcp/61790/ipfs/QmZKjsGJ6ukXVRXVEcExx9GhiyWoJC97onYpzBwCHPWqpL in 220.544µs
pinged /ip4/127.0.0.1/tcp/61790/ipfs/QmZKjsGJ6ukXVRXVEcExx9GhiyWoJC97onYpzBwCHPWqpL in 208.761µs
pinged /ip4/127.0.0.1/tcp/61790/ipfs/QmZKjsGJ6ukXVRXVEcExx9GhiyWoJC97onYpzBwCHPWqpL in 201.37µs
