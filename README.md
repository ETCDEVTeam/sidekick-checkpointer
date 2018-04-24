# ETCDEVTeam/sidekick-*

> A collection of scripts and documents outlining requirements and initial adhoc solves for a minimum-viable ETC sidechains implementation.

- [github.com/ETCDEVTeam/sidekick-tx2poa](http://github.com/ETCDEVTeam/sidekick-tx2poa). A PoA mechanism implemented through an emphemeral JS console.

- [github.com/ETCDEVTeam/sidekick-liaison](http://github.com/ETCDEVTeam/sidekick-liaison). A bash script that listens to a sidechain node and facilitates communication with an arbitrary mainnet node. As written, relies on [emerald-cli](https://github.com/ETCDEVTeam/emerald-cli).

- [github.com/ETCDEVTeam/sidekick-checkpointer](http://github.com/ETCDEVTeam/sidekick-checkpointer). A checkpointing mechanism implemented through an ephemerald JS console.

# sidekick-checkpointer

Use a JS script executed in an ephemeral geth console to pace, delegate, and validate blockchain checkpoints.
