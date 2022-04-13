# Dispute Resolution Contract (DRC) Factory

### 2.5 Dispute Resolution Contract (DRC) Factory

The APIS Dispute Resolution Contract (DRC) Factory was initially designed as a function within the Governance Contract, but was later separated into its own contract to ensure complete modularity, allowing for upgrades to the DRC when a less subjective resolution mechanism is able to be deployed, which should be the case as zero-knowledge-proofs continue to scale. The purpose of the DRC Factory is to allow API holders to vote specifically on events that have happened off-chain, namely whether a Node or Gateway provided a fraudulent or misrepresented endpoint, either to another Gateway or end-user client. API tokens staked in the GC can be used to stake in the DRC (and in the _Optimistic Rollup Contract, as described in 2.6_) simultaneously, although requiring the signing of an additional transaction on the Ethereum mainnet.
