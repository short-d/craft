# Craft Project Proposal

## Objective

Build a cross platform tool where developers can organize and play around with REST, GraphQL, gRPC, and WebSocket APIs in a single place.

## Background

There is currently no single tool allowing developers to test & organize REST, GraphQL, gRPC, WebSocket APIs together.

- Postman: REST / GraphQL
- Insomnia: REST / GraphQL
- GraphQL Playground: GraphQL
- Smart Websocket Client Chrome extension: WebSocket
- BloomRPC: gRPC

However, real world software systems often use more than one technology stack to achieve their specific performance & maintenance needs.

For smart hardware ecosystems, engineers frequently have to work with raw UDP, TCP, and Bluetooth protocols. Currently, they use Wireshark to analyze RAW network packets.

## Roadmap

### v1

- [ ] Send simple REST request to any backend with custom header, method, and body (mininal UI)
- [ ] Send GraphQL request to any backend with custom query (mininal UI) 
- [ ] Connect to any Web socket server. Send custom message and receive response from the server (mininal UI)
- [ ] Send gRPC (H2C/HTTPS) requests to any any backend (mininal UI)
- [ ] Save & group APIs into services (directories)
- [ ] Import REST apis from OpenAPI 3.0 spec
- [ ] Show GraphQL documentation after user filled in the base URL
- [ ] Import gRPC apis from .proto file
- [ ] Attach markdown document to the apis
- [ ] Export directory so that it can be version controlled
- [ ] Enable syntax highlighting for JSON payload
- [ ] Enable syntax highlighting for GraphQL query
- [ ] Enable syntax highlighting for gRPC request
- [ ] Redesign the UI so that it's clear, convenient, easy to use, and looks good

### v2

- [ ] Support Google, Facebook, and Github sign in
- [ ] Save directories to backend
- [ ] Generate shareable for a directory or a API
- [ ] Create teams and add members
- [ ] Share directories with in the team
- [ ] Provide web hooks so that devs can do continuous delivery for their directory
- [ ] Share directories to public
- [ ] Search public directories

### v3

- [ ] Mock HTTP API
- [ ] Mock GraphQL API
- [ ] Mock Web Socket API
- [ ] Mock gRPC API
- [ ] Companies maintain their public API directory
- [ ] Developers purchase quota package for paid APIs 
- [ ] Send & receive raw UDP packets
- [ ] Send & receive raw TCP packets
- [ ] Send & receive bluetooth packets
- [ ] Export UDP & TCP APIs for version control
- [ ] Mock UDP API
- [ ] Mock TCP API
- [ ] Mock Bluetooth
