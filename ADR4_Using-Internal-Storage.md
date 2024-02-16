# ADR4: Using Internal Storage

**Status**
Accepted

**Context**
The game is an offline game where users have the option to resume the game anytime. Using internal storage will allow the user to save their progress if they choose to continue the game later. It will also give the user faster access to the game’s saved data as it will not require a network to retrieve data.

**Decision**
Since the game is offline and does not need any third-party or cloud storage, it is decided that the storage will be internal.

**Consequences**
Using internal storage is safer since the user data is private. Also, without the need to access the network to acquire the game data, the process is faster. Since the game will be using the device's internal storage, the amount of data the game can store is limited. Moreover, the game data remains in the same device and is not accessible to another device without manually transferring all the data from one device to another.
