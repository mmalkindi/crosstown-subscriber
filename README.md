# Tutorial 8 - Subscriber

## Reflection

> what is `amqp`?

A: amqp is short for Advanced Message Querying Protocol.
It serves as a network protocol to help with message transfer between services.
In our case, we will be using it to transfer messages between `subscriber` and `publisher`

> what it means? `guest:guest@localhost:5672`
> what is the first `quest`, and what is the second `guest`,
> and what is `localhost:5672` is for?

A:

- `guest` (1): username for authentication
- `guest` (2): password for `guest`
- `localhost:5672`: IP address and port where RabbitMQ is running. We're using `localhost` to refer to our local machine
