# ACH Processing in UltraCamp
UltraCamp operates as an ACH Originator and can facilitate electronic payments and refunds for your customers. The ACH system allows you to transfer money between bank accounts, rather than going through the payment card networks (Visa/Mastercard, Discover, or American Express). UltraCamp operates under the rules of NACHA (National Automated Clearing House Association), which is the administrator and governor of the ACH Network.


## How Payments are Made by your Customers


Customers can add bank account information to their account from the payment page. The page requires the Account Type, Name on Account, Bank Routing Number, and Bank Account Number. It also includes an Authorization for your organization and “UltraCamp LLC” to electronically debit their account for fees incurred. This authorization is encrypted and stored in UltraCamp and will remain in effect until such authorization is revoked by the account holder. The maximum per-transaction dollar limit is $1,000,000.


ACH transactions are not real-time but are batched every morning for the previous day’s entries. ACH entries are irrevocable once they have been sent for processing and can only be voided in the short time period before they are batched.


## Prenotes for Account Validation


Any time a customer adds a new unique bank account to their account, it triggers the creation of a Prenote. A Prenote is a zero-dollar entry that is used to verify the bank account information of your customer. By NACHA rule, there is a 3-day waiting period after submitting a Prenote before a live transaction can be sent.


## Settlement Process


Customer payments take 3-4 business days to settle into the UltraCamp ParentPay holding account. Once we receive the batch, we create a new batch to send the funds to your designated bank account. This process takes an additional 3-4 business days to settle.


Customer refunds take the same amount of time and go from your account to the UltraCamp ParentPay account then to the customer account.




|  |  |
| --- | --- |
| ACH Process | Days |
| Prenote | 3 |
| Parent to UltraCamp ParentPay | 3 to 4 |
| UltraCamp ParentPay to Camp | 3 to 4 |
| Possible Processing Time | 6 to 11 business days |


 


## ACH Returns


ACH transactions can be returned for several reasons:


* Insufficient funds
* Bank account closed
* No bank account/unable to locate account
* Invalid bank account number
* Payment stopped


Returns will automatically create a “Returned ACH” transaction in the customer financial detail reversing the payment attempted. UltraCamp can also add a “Returned ACH Fee” with a penalty amount based on the type of return. You will be charged the ACH Return Fee regardless of the type of return.


## ACH Processing Fees




|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 

|  |  |
| --- | --- |
| Fee Type | Fee Amount |
| Transaction Fee | $0.50 |
| Transaction Discount Rate | 1.00% |
| ACH Batch Fee | $0.25 |
| ACH Return Fee | $2.50 |
| ACH Monthly Fee (when used) | $5.00 |
| Electronic Payment Compliance Fee | 0.10% |

 |   |

