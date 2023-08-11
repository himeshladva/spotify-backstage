## API Report File for "@backstage/plugin-app-node"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts
import { ExtensionPoint } from '@backstage/backend-plugin-api';
import { Handler } from 'express';

// @public
export interface StaticFallbackHandlerExtensionPoint {
  setStaticFallbackHandler(handler: Handler): void;
}

// @public
export const staticFallbackHandlerExtensionPoint: ExtensionPoint<StaticFallbackHandlerExtensionPoint>;
```