# Examples

This directory contains runnable examples for `@dcyfr/ai-chatbot`.

## Files

- `simple-chat/index.ts` — Minimal chatbot usage.
- `advanced-chat/index.ts` — Middleware and plugin patterns.
- `streaming-chat/index.ts` — Token streaming and chunk handling.

## Prerequisites

- Install dependencies: `npm install`

## Run examples

From package root:

- `npx tsx examples/simple-chat/index.ts`
- `npx tsx examples/advanced-chat/index.ts`
- `npx tsx examples/streaming-chat/index.ts`

## Type-check examples

- `npx tsc --noEmit --module nodenext --moduleResolution nodenext --target es2022 --strict --esModuleInterop true --skipLibCheck true examples/simple-chat/index.ts examples/advanced-chat/index.ts examples/streaming-chat/index.ts`
