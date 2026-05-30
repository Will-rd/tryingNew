# Cottagecore E-Marketing


## Description
- As a seller I want to make a profile that displays my homemade goods for sale to buyers near me. I want to choose or create a category of
handmade items and then post pictures with a description and pricing along with contact info such as pick up location, email, phone, etc.
I want users near me to easily be able to browse my shop and get in contact with me or meet me at a local market stall to purchase my goods.









## Feature: Seller Product Listing Creation

### Functional Criteria (Given/When/Then format):
- Given a logged-in seller on the dashboard, when they fill out the product form and submit, then the product appears in their listing immediately
- Given a seller submits a product with missing required fields, when they click submit, then inline error messages appear and no product is saved

### Non-Functional Criteria (checklist format):
- [ ] Page loads in under 2 seconds on 4G connection
- [ ] Image uploads are compressed to <500KB client-side
- [ ] Form validates before submission (no unnecessary API calls)
- [ ] Database query for product retrieval executes in <100ms