# maf4711


## Setup (Fabrik hygiene)

Prerequisites depend on the stack (Node, Swift, Python, Go — see repo files).

```sh
# clone
git clone <this-repo>
cd maf4711

# install (pick what exists)
# npm ci | pnpm i | pip install -r requirements.txt | swift package resolve
```

### Start

See package scripts, Makefile, or Xcode scheme in this repository.

### Verify

```sh
# if present:
# npm run verify | make checks | make test
```

> Offline note: prefer local tools; no cloud LLM SDK required for core use
> (Fabrik LLM-Provider policy / zero-cost path).

