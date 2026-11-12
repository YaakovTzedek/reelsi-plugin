# Reelsi for Cursor and Grok Bot

Connect Reelsi and let your agent create reels from a video URL, long content, a graphic, or a website, then poll status and request revisions.

This plugin points Cursor at the hosted Reelsi MCP server and lets the client run the ordinary OAuth redirect. No API keys belong in this repository.

- Website: https://reelsi.ai
- Docs: https://reelsi.ai/api
- Privacy: https://reelsi.ai/privacy
- Terms: https://reelsi.ai/terms
- Support: office@tzedek.me

## Install (Cursor / Grok Bot)

1. Install this plugin from the Cursor marketplace once it is listed, or add the MCP URL below as a custom remote server.
2. When prompted, sign in with your Reelsi account (OAuth 2.1, PKCE). Approve the requested scopes.
3. Ask one of the example prompts in a new chat.

Remote MCP URL (Streamable HTTP): `https://reelsi.ai/mcp`


## Example prompts

- Show my Reelsi credit balance and the price of a video reel, without starting a job.
- Quote (dry_run) a 20-second reel from https://example.com/talk.mp4 with bold captions, in English.
- List my latest reels and the status of the most recent one.
- When the last reel is ready, give me the MP4 URL and poster.
- Ask for a revision: make the captions bigger and the pace faster (only after the reel is ready).

## License

MIT. See LICENSE.

## Maintainer

Yaakov Tzedek. This repository is only the plugin wrapper (manifest + MCP pointer + logo). It does not contain account credentials.
