# Random
Random_id and random_pet with null provider

Each time when is executed terraform apply the result from "echo" command will be different. 

```
null_resource.server1 (local-exec): Executing: ["/bin/sh" "-c" "echo capital-emu"]
null_resource.server (local-exec): Executing: ["/bin/sh" "-c" "echo 743083192dc744be"]
null_resource.server (local-exec): 743083192dc744be
null_resource.server1 (local-exec): capital-emu
```
