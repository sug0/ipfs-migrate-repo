# ipfs-migrate-repo

Migrate an IPFS repository from its current version to the latest one
supported by [kubo](https://github.com/ipfs/kubo).

## Usage

Simply run `ipfs-migrate-repo`. The supported environment variables are:

```
===========================================================================
LATEST_REPO_VERSION | The last version to perform the migration to. If
                    | empty, this variable is inferred automatically through
                    | kubo.
===========================================================================
IPFS_PATH           | The path to an IPFS repository.
===========================================================================
DRY_RUN             | When set to 1, simply prints the migrations that
                    | would be run on the selected repository.
===========================================================================
```
