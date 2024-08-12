# testchain Consensus Breaking

1) Consensus is the agreement between nodes on the state of the blockchain. Breaking consensus means that we introduce a change that would cause nodes to disagree with the state of the blockchain, which leads to fork/splits.
2) In my blockchain, I set the configuration for alice to have a timeout_commit and timeout_propose of 5 seconds. However, I set the global variables to have a timeout_commit and timeout_propose of 12 seconds. This breaks consensus as all validators must have the same consensus parameters to agree on the blockchain state.
