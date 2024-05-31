## 👋 Frontend SDK

[![NPM Version](https://img.shields.io/npm/v/@cyware/sdk-frontend?style=for-the-badge)](https://www.npmjs.com/package/@cyware/sdk-frontend)

This is repository for the Cyware frontend SDK.

The design pattern is heavily influenced by the VSCode SDK and works mainly with the `Command` concept.

```typescript
import { Cyware } from "@cyware/sdk-frontend";

Cyware.commands.register("my-command", {
  name: "My Command",
  run: (context) => {
    // Do something
  },
});

Cyware.commandPalette.register("my-command");
```

## 💚 Community

Come join our [Discord](https://links.khulnasoft.com/www-discord) community and connect with other Cyware users! We'd love to have you as part of the conversation and help with any questions you may have.