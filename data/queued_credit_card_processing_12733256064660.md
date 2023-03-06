# Queued Credit Card Processing
Queued credit card processing allows for the handling of a large volume of transactions by temporarily storing them in a queue and processing them in batches. 


As of February 2, 2023, this feature will be the default setting for all UltraCamp clients.


## How it Works


Queued processing is an UltraCamp setting that works with any credit card provider. As payments are submitted in the checkout process, we store them in a queue and process them in order, which can take from a few seconds to several minutes depending on your volume. The payment is displayed on the customer page as a "Queued Credit Card Payment". Once the payment goes through successfully, the customer receives an automated transaction receipt. No matter the length of time it takes for the queued payment to go through, the customer will still get their Confirmation Receipt for their reservation.


For payments that fail, the customer is notified immediately with instructions to correct their payment. If no action is taken by the customer, we retry the payment a second time 24 hours later. If this payment fails, we remove the queued credit card payment from their account. Note that a failed queued payment does not cancel their registration or change their status in any way. They will retain a balance on their account.


We have a summary email that is sent each morning to the Billing Contact role that details any failed payments.


*Example email showing total activity for the previous day:*





Abandoned payments list each payment, a link to the account, and the reason for failure.


The Transaction Summary displays in the Details column the status of your credit card payments. Queued payments display their current status. When the payments transmit successfully, it is replaced with the Gateway ID.


*Example Transaction Summary report showing various queued payments and their status:*





Queued payments that fail are attempted again 24 hours later. If they fail a second time, they are removed from the account and fall off of the Transaction Summary report.


## Transactions Affected


Queued processing is **only** for payments that go through the checkout process in the shopping cart. Payments made using the "Make a Payment" method on the Public side or the Admin side of UltraCamp are not queued and are processed immediately.


## Advantages


Smoother registration process- During high demand registration events, the heaviest use of server resources are taken by waiting for payment processing responses on the checkout page. Queued processing puts this in the background and allows rapid checkout with fewer slowdowns.


Higher conversion rate- About a third of all abandoned registrations happen in the final step of the registration process. Queued processing eliminates the abandonment of registrations from failed payments and helps with your conversion rate. Internal monitoring in UltraCamp shows over 80% of failed payments with queued processing are fixed by the parent on the same day.


Improved UltraCamp performance - By moving most credit card transactions to a queued model, we remove the bottleneck of waiting for credit card processor responses for checkout. During high demand, this can be noticeable by your parents.


## Opt-out Ability


Queued processing's advantages are many, but if you do not want to use it for your organization, there is an opt-out ability for smaller clients. If your largest registration day of the year is less than 500 reservations, you can request to remove Queued processing by submitting a support ticket. Queued processing is mandatory for larger organizations.


 

