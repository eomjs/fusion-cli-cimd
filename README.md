# fusion-cli CIMD client metadata

  This repo hosts the OAuth Client Identifier Metadata Document (RFC 7591bis)
  used by `fusion-cli login` to authenticate against the Autodesk Fusion Data
  MCP server.

  The URL `https://eomjs.github.io/fusion-cli-cimd/client-metadata.json` is the
  OAuth `client_id`. **Do not move, rename, or delete this repo.** Doing so
  invalidates every previously-issued token.

  To update content (e.g., add a redirect_uri), edit `client-metadata.json` and
  push. The URL stays stable.
