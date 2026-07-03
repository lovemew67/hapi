# Usage

```
bun install
bun run download:tunwg
bun run build:web
cd hub && bun run generate:embedded-web-assets
cd cli && bun run build:exe:allinone -- --target bun-darwin-arm64
```
```
hapi server --host=100.x.y.z --port=3006
HAPI_API_URL=http://100.x.y.z:3006 hapi
```
