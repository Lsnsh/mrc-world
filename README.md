# nestjs-schematics/nest-cli-generate-resource-missing-trailing-comma

## Clone

```shell
git clone git@github.com:Lsnsh/mrc-world.git -b nestjs-schematics/nest-cli-generate-resource-missing-trailing-comma
```

## Reproduction

1. `npm install`
2. `npx nest generate resource car`
   1. What transport layer do you use? `REST API`
   2. Would you like to generate CRUD entry points? `No`
3. open `./src/car/car.module.ts`
4. see the error
