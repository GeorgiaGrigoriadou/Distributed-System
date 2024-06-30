# Distributed System for Music Transfer
This project implements a distributed system that allows for the transfer of music files from a PC to an Android phone using IP and port communication. The system is composed of several components, each handling different roles in the transfer process.

## Project Structure
- **.idea** : Contains the project-specific configuration files.
- **android** : Contains the Android application files.
- **broker** : Manages the distribution of music files and coordinates between publishers and subscribers.
- **publisher** : Responsible for storing and serving music files.
- **subscriber** : Requests and receives music files from publishers via the broker.
