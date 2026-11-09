# Remote File Management Protocol (RFMP)

A multi-threaded client-server application for remote file management, built as the final project for **CSEC-201: Programming for Information Security** at RIT Dubai. It is written in **Python and C** using socket programming and secures the communication between client and server with encryption.

## Features
- Multi-threaded server that handles multiple client connections
- Remote file management over a custom application-layer protocol
- RSA-based key exchange to establish a shared secret
- AES (with a Caesar-cipher component) to encrypt client-server messages and file transfers
- [Add: supported commands, e.g. upload, download, list, delete]

## Tech Stack
Python, C, TCP sockets, threading, RSA, AES

## Usage

## Notes
- Built for educational purposes to practice secure network programming. It is not intended for production use.
