<!--
order: 5
-->

# Clients

A user can query the `x/recovery` module using the CLI, gRPC or REST.

## CLI

Find below a list of `fcod` commands added with the `x/recovery` module. You can obtain the full list by using the `fcod` -h command.

### Queries

The query commands allow users to query Recovery state.

**`params`**
Allows users to query the module parameters.

```bash
fcod query recovery params [flags]
```

## gRPC

### Queries

| Verb   |              Method              |           Description |
| :----- | :------------------------------- | :-------------------- |
| `gRPC` | `evmos.recovery.v1.Query/Params` | `Get Recovery params` |
| `GET`  |   `/evmos/recovery/v1/params`    | `Get Recovery params` |
