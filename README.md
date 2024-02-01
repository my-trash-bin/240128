# 240128 - Sample DB table structure

...for online market

## Naming Conventions

- Fields that are computed caches, depending on other fields, should have names ending with 'Cache'.
- Fields that are copied to preserve values at that time, should have names ending with 'Snapshot'.
- String fields containing a JSON object of a specific type should have names ending with 'Json'.
  - same rule is applied for bbcode,

## feature list

- common, admin, system
  - [ ] notification
  - [ ] announcement
  - [x] (system) file management (reference count)
- login
  - [x] by id & password
  - [x] by social account
  - [x] reset password by email
  - [x] can't reset password to previously used password
  - [x] attempt history
  - [ ] toggle inactivity
  - [ ] remove account
- profile
  - [x] unique nickname
  - [x] profile image
  - [x] rich text introduction including image
  - [x] comment for user
  - [x] report user
- friend, follow
  - [x] friend
  - [x] chat with friend
  - [x] follow
  - [ ] gift products
- category
  - [ ] hierarchical categories
- buy product
  - [x] comment
  - [x] inquiry
  - [x] report
  - [x] cart
  - [ ] order
  - [ ] buy
  - [ ] subscription service
  - [x] wishlist
  - [x] review
  - [ ] cancel (digital product)
  - [ ] return (physical product)
  - [ ] refund
  - [ ] cashback point
  - [ ] loyalty programs
- sell product
  - [x] sell
  - [x] group
  - [ ] cancel order
  - [ ] Restrict select item combinations
  - [ ] user role in group
  - [x] draft, review by admin
  - [x] inquiry, message
  - [x] review (snapshot)
  - [ ] affiliate marketing model
  - [ ] statistics / analytics
- event
  - [ ] redeem
  - [ ] promotion
    - [ ] restrict promotion combinations
  - [ ] coupon
    - [ ] restrict coupon combinations
- transaction
  - [x] log
  - [ ] reference related items
- miscellaneous
  - [ ] decorate user profile using physical products owned
  - [ ] real digital content viewer
