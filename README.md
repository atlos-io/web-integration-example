"# web-integration-example" 

Copy and paste the code from the index.html file to your checkout page.

Substitute the placeholder text with:

merchant_id     - your wallet address
order_id        - Used to track the order. If you only sell one product, you can pass an empty string ''.
amount          - the order amount in USD, e.g. 1234.56
handleSuccess   - (optional) a callback function to call when the payment is completed successfully
handleCanceled  - (optional) a callback function to call when the payment widget is closed and the payment was not completed

Important: the widget will not be able to connect to a wallet if ran locally.
