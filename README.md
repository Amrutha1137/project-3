# Chat Message History Manager

## Overview
This project is a C++ console application that manages chat messages with undo and redo functionality.  
It uses a **queue** to store incoming messages, a **stack** for undo/redo actions, and keeps track of **timestamps**.

## Features
- Add new messages with timestamp.
- View all messages in the inbox.
- Undo last sent message.
- Redo previously undone message.
- Simple text-based menu.

## Technologies Used
- C++  
- Queue and Stack (STL)  
- ctime library for timestamps  

## How to Run
1. Compile:
   ```bash
   g++ chat_manager.cpp -o chat_manager
