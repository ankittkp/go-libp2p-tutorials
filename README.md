# go-libp2p-tutorials

# Peer-to-peer basics
In peer-to-peer (P2P) networking, a group of computers are linked together with equal permissions and responsibilities for processing data. Unlike traditional client-server networking, no devices in a P2P network are designated solely to serve or to receive data. Each connected machine has the same rights as its “peers”, and can be used for the same purposes. Peers are both clients and servers at the same time.

# Uses of Peer-to-peer
P2P is used to share all kinds of computing resources such as processing power, network bandwidth, or disk storage space. However, the most common use case for peer-to-peer networks is the sharing of files on the internet. Peer-to-peer networks are ideal for file sharing because they allow the computers connected to them to receive files and send files simultaneously.


# Example
When you download the same file from a peer-to-peer network, using a BitTorrent platform as a starting point, the download is performed differently. The file is downloaded to your computer in bits and parts that come from many other computers that also connected to the same P2P network and already have that file or at least parts of it. At the same time, the file is also sent (uploaded) from your computer to other devices that are asking for it. This situation is similar to a two-way road: the file is like multiple small cars coming to your PC, while also leaving to others when it is requested.

- Windows 10 updates are delivered both from Microsoft's servers and through P2P.
- Sharing large files over the internet is often done using a P2P (peer-to-peer) network architecture. For example, some online gaming platforms use P2P for downloading games between users. Blizzard Entertainment distributes Diablo III, StarCraft II, and World of Warcraft using P2P. Another large publisher, Wargaming, does the same with their World of Tanks, World of Warships, and World of Warplanes games. Others, like Steam or GOG, choose not to use P2P and prefer maintaining dedicated download servers around the world.


# libp2p
libp2p is a modular system of protocols, specifications and libraries 
that enable the development of peer-to-peer network applications. libp2p is a networking stack and library modularized out of The IPFS Project, and bundled separately for other tools to use

# listening-node - 1st terminal
./libp2p-node
libp2p node address: /ip4/127.0.0.1/tcp/61790/ipfs/QmZKjsGJ6ukXVRXVEcExx9GhiyWoJC97onYpzBwCHPWqpL

# second-node which has the address of first node with some ping responses - 2nd terminal

./libp2p-node /ip4/127.0.0.1/tcp/61790/ipfs/QmZKjsGJ6ukXVRXVEcExx9GhiyWoJC97onYpzBwCHPWqpL
libp2p node address: /ip4/127.0.0.1/tcp/61846/ipfs/QmVyKLTLswap3VYbpBATsgNpi6JdwSwsZALPxEnEbEndup
sending 5 ping messages to /ip4/127.0.0.1/tcp/61790/ipfs/QmZKjsGJ6ukXVRXVEcExx9GhiyWoJC97onYpzBwCHPWqpL
pinged /ip4/127.0.0.1/tcp/61790/ipfs/QmZKjsGJ6ukXVRXVEcExx9GhiyWoJC97onYpzBwCHPWqpL in 431.231µs
pinged /ip4/127.0.0.1/tcp/61790/ipfs/QmZKjsGJ6ukXVRXVEcExx9GhiyWoJC97onYpzBwCHPWqpL in 164.94µs
pinged /ip4/127.0.0.1/tcp/61790/ipfs/QmZKjsGJ6ukXVRXVEcExx9GhiyWoJC97onYpzBwCHPWqpL in 220.544µs
pinged /ip4/127.0.0.1/tcp/61790/ipfs/QmZKjsGJ6ukXVRXVEcExx9GhiyWoJC97onYpzBwCHPWqpL in 208.761µs
pinged /ip4/127.0.0.1/tcp/61790/ipfs/QmZKjsGJ6ukXVRXVEcExx9GhiyWoJC97onYpzBwCHPWqpL in 201.37µs
