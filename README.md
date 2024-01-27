# Frietor Saar Testnet Snapshots

Welcome to the Frietor Saar Testnet Snapshots repository! This repository hosts continuous snapshots of the Frietor Saar blockchain testnet. Snapshots are pre-generated backups of the blockchain state, providing an efficient way for users to bootstrap their nodes without syncing from scratch.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Available Snapshots](#available-snapshots)
- [Usage](#usage)
- [License](#license)
- [Contact](#contact)

## Introduction

The Frietor Saar Testnet Snapshots project aims to simplify the process of setting up and running nodes on the Frietor Saar blockchain testnet by providing continuous snapshots. These snapshots capture the current state of the testnet, allowing users to quickly restore backups without the need for a full synchronization.

## Features

- **Continuous Snapshots:** Snapshots are continuously updated to reflect the latest state of the Frietor Saar Testnet.

- **Compressed Snapshots:** Snapshot files are compressed to 100 MB or less, reducing storage requirements.

- **Easy Restoration:** Users can restore backups while starting their nodes using the provided compressed snapshots.

## Getting Started

To get started with the Frietor Saar Testnet Snapshots, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Esportzvio/FrietorSaar_Snapshots.git
   cd FrietorSaar_Snapshots
   ```

2. **Choose a Compressed Snapshot:**

   - Browse the repository to find the desired compressed snapshot file (e.g., `Snapshot-0000-00-00.dat.gz`).

3. **Restore Backup while Starting Nodes:**
   ```bash
   gunzip -c Snapshot-0000-00-00.dat.gz | ./frietor server --restore -
   ```

## Available Snapshots

<!-- Add links to compressed snapshot files -->

## Usage

- Choose a compressed snapshot file from the [Available Snapshots](#available-snapshots) section.
- Follow the [Getting Started](#getting-started) instructions to clone the repository and restore a backup while starting nodes.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any inquiries or support, feel free to reach out to [support@esportzvio.com].

Happy testing with Frietor Saar Testnet Snapshots!
