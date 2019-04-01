# 31. Ownership

- Add the `user_id` column to the `products` table.
- When creating a product, set the User ID.
- When fetching or listing products include the User ID.
- When updating or deleting products ensure that the client either has
  `RoleAdmin` or is the owner of the specified product.


## File Changes:

```
Modified cmd/sales-api/internal/handlers/products.go
Modified internal/platform/database/schema/migrations.go
Modified internal/products/products.go
```