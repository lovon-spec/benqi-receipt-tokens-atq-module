# BENQI lending market receipt token tags

ATQ draft for Avalanche (43114) using the current deployment of Messari subgraph 8ZjJGsaKea7WwLJPJNdHXPGsvXDe3iq2231aRjgBPisi, listed in Messari's decentralized network catalogue. Every output address is derived from markets at one indexed block hash, with complete unique-ID cursor pagination. The module emits only lending market receipt token contracts, including historical instances.

Use Yarn to build, then import returnTags from dist/main.mjs and pass the decimal chain ID plus a Graph API key. All runtime logic is in src/main.mts. Errors and inconsistent metadata fail the whole call.

Unpublished local preparation draft. No review or filing authority.
