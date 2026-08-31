# ShopZora PK — GitHub Test Package

## Fast test
Upload the **contents** of this folder to a GitHub repository. Enable **Settings → Pages → Deploy from branch**. Open the generated Pages URL.

This version works as a **static demo immediately**:
- responsive mobile/desktop storefront
- Shop/search/category filtering
- product page
- cart
- COD checkout
- order confirmation
- local demo admin
- product/order management in browser localStorage

### Demo admin
- Email: `admin@shopzora.pk`
- Password: `ShopZora123!`

### Important
This package intentionally does **not** put any secret/API key in the frontend. For a real multi-device store, connect Supabase with a public/publishable browser key and RLS policies. Do not put a service-role/secret key in GitHub.

### Real production database
Create `products` and `orders` tables and the `admin_users` authorization table, then add RLS policies. The current demo is safe to test on GitHub, but localStorage orders are browser-specific and are not a real shared ecommerce database.

### Product
Default product is the 3-in-1 Vegetable & Fruit Cutter at Rs. 1,750. Replace `images/products/cutter.svg` with your real product image.
