# Graph-cli-commands-cheatsheet

0.64

flags/options for various commands in the Graph Protocol's `graph-cli` tool:

### Add Command
- `--abi`: Path to the contract ABI.
- `--start-block`: Block number to start indexing from.
- `--contract-name`: Name of the contract.
- `--merge-entities`: Merge entities with the same name.
- `--network-file`: Networks config file path.

### Auth Command
- `--product`: Product for authentication.
- `--studio`: Shortcut for `--product subgraph-studio`.

### Build Command
- `--ipfs`: Upload build results to an IPFS node.
- `--output-dir`: Output directory for build results.
- `--output-format`: Output format for mappings.
- `--skip-migrations`: Skip subgraph migrations.
- `--watch`: Regenerate types when subgraph files change.
- `--network`: Network configuration from networks config file.
- `--network-file`: Networks config file path.

### Clean Command
- `--codegen-dir`: Directory for "graph codegen" code.
- `--build-dir`: Directory for "graph build" code.

### Codegen Command
- `--output-dir`: Output directory for generated types.
- `--skip-migrations`: Skip subgraph migrations.
- `--watch`: Regenerate types when subgraph files change.
- `--uncrashable`: Generate Float Subgraph Uncrashable helper file.
- `--uncrashable-config`: Directory for uncrashable config.

### Create Command
- `--node`: Graph node to create the subgraph in.
- `--access-token`: Graph access token.

### Deploy Command
- `--product`: Select a product for authentication.
- `--studio`: Shortcut for `--product subgraph-studio`.
- `--node`: Graph node for initialization.
- `--deploy-key`: User deploy key.
- `--access-token`: Graph access token (deprecated).
- `--version-label`: Version label for deployment.
- `--ipfs`: Upload build results to an IPFS node.
- `--ipfs-hash`: IPFS hash of the subgraph manifest.
- `--headers`: Custom headers for IPFS HTTP client.
- `--debug-fork`: ID of a remote subgraph for GraphQL queries.
- `--output-dir`: Output directory for build results.
- `--skip-migrations`: Skip subgraph migrations.
- `--watch`: Regenerate types when subgraph files change.
- `--network`: Network configuration from networks config file.
- `--network-file`: Networks config file path.
- `--from-hosted-service`: Hosted service Subgraph Name for studio deployment.

### Init Command
- `--protocol`: Protocol to use.
- `--product`: Selects the product for initialization.
- `--studio`: Shortcut for `--product subgraph-studio`.
- `--node`: Graph node for initialization.
- `--allow-simple-name`: Use a subgraph name without a prefix.
- `--from-contract`: Scaffold based on an existing contract.
- `--from-example`: Scaffold based on an example subgraph.
- `--contract-name`: Name of the contract.
- `--index-events`: Index contract events as entities.
- `--skip-install`: Skip installing dependencies.
- `--skip-git`: Skip initializing a Git repository.
- `--start-block`: Block number to start indexing from.
- `--abi`: Path to the contract ABI.
- `--spkg`: Path to the SPKG file.
- `--network`: Network the contract is deployed to.

### Local Command
- `--node-logs`: Print the Graph Node logs.
- `--ethereum-logs`: Print the Ethereum logs.
- `--compose-file`: Custom Docker Compose file for additional services.
- `--node-image`: Custom Graph Node image for testing.
- `--standalone-node`: Use a standalone Graph Node outside Docker Compose.
- `--standalone-node-args`: Arguments for the standalone Graph Node.
- `--skip-wait-for-ipfs`: Don't wait for IPFS to be up.
- `--skip-wait-for-ethereum`: Don't wait for Ethereum to be up.
- `--skip-wait-for-postgres`: Don't wait for Postgres to be up.
- `--timeout`: Time to wait for service containers.

### Test Command
- `--coverage`: Run tests in coverage mode.
- `--docker`: Run tests in a docker container.
- `--force`: Overwrite folder/file when downloading or rebuild docker image.
- `--logs`: Log information about the OS, CPU model, and download URL.
- `--recompile`: Force-recompile tests.
- `--version`: Choose the version of the rust binary to download/use.
