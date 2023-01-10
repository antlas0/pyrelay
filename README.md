# What is PyRelay?

PyRelay is a python implementation of a NOSTR Relay, using asyncio.
Don't know whats NOSTR is? check it out [here](https://nostr.com/).

# Quick start
 
### Installing
PyRelay require python 3.11 and uses poetry as dependency management tool.
I suggest setting up virtual env before running locally, and make sure to install poetry to setup other requirements.

Install using git
```bash
git clone https://github.com/johnny423/pyrelay
cd pyrelay
```
### Run with docker compose
```bash
docker compose up
```

### Run Locally
Install dependencies, without dev dependencies
```bash
poetry install --no-dev
```

Run the server
```bash
python ./pyrelay/relay/server.py
```

# Developer Setup
Download and install the latest version of git.

Configure git with your username and email.

```bash
git config --global user.name 'your name'
git config --global user.email 'your email'
```
Make sure you have a GitHub account.

Clone the repository locally.
```bash
git clone https://github.com/johnny423/pyrelay
cd pyrelay
```

Install dependencies, include dev dependencies 
```bash
poetry install
```

### Running tests 
You can run the tests with the scripts 
```bash
./scripts/test.sh
```

# Support status

[Check the NIPs in here](https://github.com/nostr-protocol/nips)

## Supported NIPs

| supported | NIP    | description                                                  |
|-----------|--------|--------------------------------------------------------------|
| V         | NIP-01 | Basic protocol flow description                              |
| V         | NIP-02 | Contact List and Petnames                                    |
| X         | NIP-03 | OpenTimestamps Attestations for Events                       |
| X         | NIP-04 | Encrypted Direct Message                                     |
| X         | NIP-05 | Mapping Nostr keys to DNS-based internet identifiers         |
| X         | NIP-06 | Basic key derivation from mnemonic seed phrase               |
| X         | NIP-07 | window.nostr capability for web browsers                     |
| X         | NIP-08 | Handling Mentions                                            |
| X         | NIP-09 | Event Deletion                                               |
| X         | NIP-10 | Conventions for clients' use of e and p tags in text events. |
| X         | NIP-11 | Relay Information Document                                   |
| X         | NIP-12 | Generic Tag Queries                                          |
| X         | NIP-13 | Proof of Work                                                |
| X         | NIP-14 | Subject tag in text events.                                  |
| X         | NIP-15 | End of Stored Events Notice                                  |
| X         | NIP-16 | Event Treatment                                              |
| X         | NIP-18 | Reposts                                                      |
| X         | NIP-19 | bech32-encoded entities                                      |
| X         | NIP-20 | Command Results                                              |
| X         | NIP-22 | Event created_at Limits                                      |
| X         | NIP-25 | Reactions                                                    |
| X         | NIP-26 | Delegated Event Signing                                      |
| X         | NIP-28 | Public Chat                                                  |
| X         | NIP-33 | Parameterized Replaceable Events                             |
| X         | NIP-36 | Sensitive Content                                            |
| X         | NIP-40 | Expiration Timestamp                                         |