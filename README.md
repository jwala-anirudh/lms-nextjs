## Seed database with categories

```
node scripts/seed.ts
```

## Prisma commands

### Local prisma studio

```
npx prisma studio
```

### Create db models with prisma

```
npx prisma generate
```

### Update remote mysql server

```
npx prisma db push
```

### Reset entire prisma db

```
npx prisma migrate reset
```

### Stripe payment gateway

After installing the cli, use the following command

```
stripe listen --forward-to localhost:3000/api/webhook
```
