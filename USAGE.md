<!-- Start SDK Example Usage [usage] -->
```typescript
import { Payle } from "payle-docs";

const payle = new Payle({
  apiKeyAuth: "<YOUR_API_KEY_HERE>",
});

async function run() {
  const result = await payle.account.getAccount();

  // Handle the result
  console.log(result);
}

run();

```
<!-- End SDK Example Usage [usage] -->