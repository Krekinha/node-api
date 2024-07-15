build commands: npm ci && npm run build
start command: npm run start
next


antigo json
{
  "name": "api",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "engines": {"node": "18"},
  "scripts": {
    "dev": "tsx src/server.ts",
    "build": "tsup src",
    "start": "node dist/server.js "
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "devDependencies": {
    "@types/node": "^20.14.10",
    "prisma": "^5.16.2",
    "tsup": "^8.1.0",
    "tsx": "^4.16.2",
    "typescript": "^5.5.3"
  },
  "dependencies": {
    "@prisma/client": "^5.16.2",
    "fastify": "^4.28.1",
    "zod": "^3.23.8"
  }
}