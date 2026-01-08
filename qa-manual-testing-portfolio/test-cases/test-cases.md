# Manual Test Cases

| ID | Title | Preconditions | Steps | Expected Result | Priority |
|----|------|---------------|-------|----------------|----------|
| TC-01 | Register with valid data | User logged out | Submit valid form | Account created | High |
| TC-02 | Invalid email registration | User logged out | Submit invalid email | Error shown | High |
| TC-03 | Login valid user | Account exists | Login | Success | High |
| TC-04 | Login invalid password | Account exists | Wrong password | Error shown | High |
| TC-05 | Add product to cart | Logged in | Add item | Item added | High |
| TC-06 | Duplicate product add | Logged in | Add twice | Quantity increases | Medium |
| TC-07 | Empty form submit | Logged out | Submit empty form | Validation errors | High |
| TC-08 | Header navigation | Any | Click links | Correct page | Medium |
| TC-09 | Logout | Logged in | Click logout | User logged out | Medium |
| TC-10 | Refresh cart | Item added | Refresh page | Cart persists | High |
