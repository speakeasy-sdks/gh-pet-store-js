<!-- Start SDK Example Usage [usage] -->
```typescript
import { PetStore } from "pet-store";

async function run() {
    const sdk = new PetStore();

    const res = await sdk.pets.createPets();

    if (res.statusCode == 200) {
        // handle response
    }
}

run();

```
<!-- End SDK Example Usage [usage] -->