# Pi-Hole Parental Controls Lists

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [Disclaimer](#disclaimer)

## Introduction
Welcome to the Pi-Hole Parental Controls Lists repository! This repository aims to provide curated whitelists and blacklists specifically tailored to enhance the security and safety of home networks, particularly for families with children. By utilizing these lists with Pi-Hole, an open-source network-wide ad blocker, you can effectively manage and restrict access to potentially harmful or inappropriate content on your home network.

## Getting Started
To get started with using the lists provided in this repository, you need to have Pi-Hole installed and configured on your network. If you haven't already set up Pi-Hole, please refer to the official Pi-Hole documentation for installation instructions suitable for your environment.

Once Pi-Hole is set up, you can integrate the lists provided in this repository by following these steps:

1. Clone or download this repository to your local machine or Pi-Hole server.
2. Navigate to your Pi-Hole admin dashboard (http://pi-hole-ip/admin).
3. Go to the "Group Management" section in the Pi-Hole admin dashboard.
4. Create a new group specifically for parental controls (e.g., "Parental Control Group").
5. In the newly created group, navigate to the "Adlists" tab.
6. Add the URLs of the desired lists (whitelists and blacklists) provided in this repository to the adlists section. Ensure to enable the "Group Management" feature.
7. Save your changes and allow Pi-Hole to update and apply the new lists.
8. Optionally, configure any additional settings or customizations according to your preferences in the Pi-Hole admin dashboard.

## Contributing
Contributions to this repository are welcome and encouraged! If you have suggestions for additional domains to whitelist or blacklist, or if you encounter any issues with the existing lists, please feel free to open an issue or submit a pull request. Your contributions will help improve the effectiveness and reliability of these lists for the entire community.

## Disclaimer
While the lists provided in this repository are curated to enhance the security and safety of home networks, it's important to note that no solution is foolproof. Parents and guardians are encouraged to actively monitor and supervise their children's internet usage, in addition to utilizing technical controls such as Pi-Hole. This repository and its maintainers are not responsible for any misuse or unintended consequences arising from the use of these lists.

