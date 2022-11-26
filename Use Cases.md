
| Use Case | Description | Associated Requirements |
| --- | --- | --- |
| UC-01  Beginning session | A cashier will create a new session at the register. The register then will create a new session where barcodes will be read in and recorded. | R-01 |
| UC-02 Iteming Scanning | A cashier will scan the barcode of an item. The register will then check the database for a matching item. If the barcode was successfully read then the item is added to the cart for the session as well as other info (ie price, name). If the barcode code is not read “UNKNOWN BARCODE” will be displayed and it will allow the cashier to manually input the code. | R-03 <br> R-04 <br> R-09 |
| UC-03 Payment Processing | Once all items have been scanned, the cashier can start the payment process. The cashier will select the payment type on the register. The register displays the total of the purchase and selected payment method to the customer. The customer will complete the purchase, either by cash or by completing it at the register with a debit or credit card. Once the payment has been received the register will be updated by either the cashier or the 3rd party system | R-05 |
| UC-04 Ending Transaction | Once the payment is verified the cashier will end the session. The register will then print a receipt for the customer and cashier. The receipt will contain all products name, quantity, and price. It will also contain details on transactions. | R-06 |
| UC-05 Canceling Product | The cashier will be able to remove a product form the current session through the keyboard. The register will remove it from the cart and subtract it from the current total. | R-07 |


