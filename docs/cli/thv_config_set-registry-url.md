## thv config set-registry-url

Set the MCP server registry URL

### Synopsis

Set the URL for the remote MCP server registry.
This allows you to use a custom registry instead of the built-in one.

Example:
  thv config set-registry-url https://example.com/registry.json

```
thv config set-registry-url <url> [flags]
```

### Options

```
  -p, --allow-private-ip   Allow setting the registry URL, even if it references a private IP address
  -h, --help               help for set-registry-url
```

### Options inherited from parent commands

```
      --debug   Enable debug mode
```

### SEE ALSO

* [thv config](thv_config.md)	 - Manage application configuration

