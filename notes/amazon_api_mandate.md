# Amazon API Mandate

Jeff Bezos wrote the following memo to his employees around 2002. It got known as the **Amazon API Mandate** (or Bezos API Mandate).

1. All teams will henceforth expose their data and functionality through service interfaces.

2. Teams must communicate with each other through these interfaces.

3. There will be no other form of interprocess communication allowed: no direct linking, no direct reads of another team’s data store, no shared-memory model, no back-doors whatsoever. The only communication allowed is via service interface calls over the network.

4. It doesn’t matter what technology is used. HTTP, Corba, Pubsub, custom protocols — doesn’t matter.

5. All service interfaces, without exception, must be designed from the ground up to be externalizable. That is to say, the team must plan and design to be able to expose the interface to developers in the outside world. No exceptions.

6. Anyone who doesn’t do this **will be fired**.