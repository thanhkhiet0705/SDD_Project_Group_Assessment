# SDD_Project_Group_Assessment

## SDD Task List Distribution
- Hoang: Product and Trade Management
- Phuong: Search and Discovery
- Khiet: User Management
- Franky: Shopping Cart and Order Management

## SDD Database Design:
User:
- userID (PK)
- email
- name(including First and Last)
- phoneNumber
- address

Product:
- productID (PK)
- productName
- productSpec
- description

Category:
- cateID (PK)
- cateName

Trade:
- tradeID (PK)
- date
- price
- status
- userID (FK)

Order:
- orderID (PK)
- productID (FK)
- userID (FK)
- dateOfOrder
- price
- status

## Required Module:
- HTTP - Allows for data to be transferred over HTTP.
- Events - Allows utilities to work with events and the Event Emitter, which is the heart of Node.js
- URL - Helps in parsing and formatting URLs
- Stream - Helps to work with streaming data, such as reading and writing along with network communications
- Crypto - Provide cryptographic functionality - hashing, encryption
- PATH - Helps with working with file and directory paths
- Query String - Provides utilities to parse and format query strings for URLS
- OS - Provides basic operating-system related utility functions
- File System (fs) - An API for interacting with local file system
- Util

## File Organisation:
Database:
- 
