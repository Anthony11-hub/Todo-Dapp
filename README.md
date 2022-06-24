# Todo-Dapp
This is a decentralized peer to peer todo list application created with gun js 

Gun uses relay peers which automatically run a signaling server inside of them but can also be fully decentralized. These peers have no central logic and even if peers fail to establish WebRTC connection, they can use a DAM (Daisy-Chain Ad-hoc Mesh Network) which relays messages to peers that are not directly connected.

#Blockchain Vs Gun
Unlike blockchain which has to store all the data on all peers, Gun can have any peer store any/all data. What is stored is usually decided by what data that peer is subscribed to. Relay peers will try to opt into 'relay-peer-mode' and store everything if they can
