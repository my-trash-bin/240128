# 240128 - Sample DB table structure

...for online market

## Naming Conventions

- Fields that are computed caches, depending on other fields, should have names ending with 'Cache'.
- Fields that are copied to preserve values at that time, should have names ending with 'Snapshot'.
- String fields containing a JSON object of a specific type should have names ending with 'Json'.
  - same rule is applied for bbcode,

## feature list

- [x] User, Authentication, OAuth, password reset, password history
- [x] User relationships (friend, follow)
- [x] File management
- [x] Article management (for product description, review, message, etc.)
- [x] Product Review
- [x] Inquiry
- [x] Digital product - validity duration
- [x] Physical product - original, addon, select, options
- [x] User inventory
- [ ] Product draft, review by admin
- [ ] Report malicious product
- [ ] Return physical product
- [ ] Refund
- [ ] Cart
- [ ] Order
- [ ] Promotion
- [ ] Announcement
- [ ] Redeem
- [ ] Restrict select item combinations
- [ ] Coupon
- [ ] Restrict coupon combinations
- [ ] Cashback point
- [ ] Wishlist
- [ ] Gift
- [ ] Chat
- [ ] User role in group
- [ ] Notification
- [ ] Subscription service
- [ ] Affiliate Marketing Model
- [ ] Loyalty Programs
- [ ] Statistics / Analytics
- [ ] User profile page decoration using physical products
