# Simple Messenger

Shared services:

- Keycloak
- Kafka (ZooKeeper)
- Postgres

Microservices:

- Service Discovery (Eureka Server)
- Gateway (Cloud Gateway)
- Client
- Message
- Controller

Containers:

1. Simple Messenger Discovery
2. Simple Messenger Client
3. Simple Messenger Message
4. Simple Messenger Controller
5. Simple Messenger Gateway

Business functions:

1. Client (7):
    - [X] Authorization
    - [ ] Update refresh token (user, admin)
    - [ ] Registration
    - [ ] Check exist mail (user, admin)
    - [ ] Get roles (admin)
    - [ ] Get clients (admin)
    - [ ] Delete client by uuid (admin)
2. Message (5):
    - [ ] Post message (user, admin)
    - [ ] Delete one message (user, admin)
    - [ ] Delete one message by uuid (admin)
    - [ ] Delete all message by mail (admin)
    - [ ] Get messages by mail (user, admin)
3. Controller (3):
    - [ ] Delete message by uuid (admin)
    - [ ] Delete client + messages (admin)
    - [ ] Post realm role to client (admin)