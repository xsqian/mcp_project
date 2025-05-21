``` sh
docker build --platform linux/amd64 -t xsqian/my-mcp-server .

docker run -p 8001:8001 -it my-mcp-server

docker push xsqian/my-mcp-server
```

### to inspect the MCP server, run the following:

``` js
npx @modelcontextprotocol/inspector
```