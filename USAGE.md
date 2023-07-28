<!-- Start SDK Example Usage -->


```typescript
import { PetStore } from "pet-store";
import { CreatePetsResponse } from "pet-store/dist/sdk/models/operations";

const sdk = new PetStore();

sdk.pets.createPets().then((res: CreatePetsResponse) => {
  if (res.statusCode == 200) {
    // handle response
  }
});
```
<!-- End SDK Example Usage -->