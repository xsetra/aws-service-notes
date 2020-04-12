# Delegate Access to Billing Console
IAM users cannot access billing data until the account owner activates IAM access and attaches policies to user or role.

- My Account -> IAM User and Role Access to Billing Information -> Edit -> Activate IAM Access
- Create BillingFullAccess policy by choosing Billing service
- Create BillingReadOnlyAccess policy by choosing Billin service with Read permission.
- Assign this policy to Groups and Users.