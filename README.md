<div>
  <h1 align="center">
    <a href="https://github.com/nischaldutt/mytorrent-client/">BitTorrent Client in Node.js</a>
  </h1>
</div>

## Overview

This project is a BitTorrent client implemented in Node.js, allowing users to download files from torrent files. It supports peer-to-peer file sharing with features like torrent file parsing, peer connection establishment, and piece management, it provides an efficient and reliable way to download files from the BitTorrent network using a job queue. Whether you're a developer exploring the BitTorrent protocol or a user seeking a customizable torrent client, this project is open for improvements and feedback.



## Features

- **Torrent Protocol Compliance:** Implementation follows the BitTorrent protocol specifications for seamless interaction with the network.
- **Torrent File Parsing:** Parsing of torrent files ensures proper extraction of metadata and file details, as per the BitTorrent protocol.
- **Peer Connection Establishment:** Establishing connections with tracker and peers.
- **Piece Management:** Managing file pieces according to protocol guidelines, ensuring reliable and orderly downloading.

## Prerequisites

- Node.js

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   
2. Navigate to the project directory:

    ```bash
    cd bittorrent-client

3. Install dependencies:

    ```bash
    npm install

## Usage
  
- Run the BitTorrent client with the following command:
  
    ```bash
    node index.js <path-to-torrent-file-to-download>

- Example

    ```bash
    node index.js example.torrent

