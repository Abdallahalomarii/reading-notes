# Payment Processing

- ### Bank Account and Merchant Account:

    - It all starts with having a bank checking account in place. However, for credit card processing, a Merchant Account is essential. This account acts as a connection to the credit card processing network, ensuring secure and accurate processing of credit card transactions. Think of it as the modern version of the old card-swipe machine.

- ### Internet Merchant Account:

  - An Internet Merchant Account is a specialized version of a regular Merchant Account designed for accepting online credit card transactions. Students should inquire whether their Merchant Account is internet-enabled and compatible with major Payment Gateways, which will be discussed next.

- ### Payment Gateway:

  - The Payment Gateway serves as a bridge between the customer's credit card information and the Internet Merchant Account, ensuring secure transmission. While the Gateway handles routing and fraud checks, the approval or decline of transactions is performed by the Merchant Account. Major Payment Gateways like Authorize.net, PayPal, and First Data simplify this process, even creating the Internet Merchant Account for you.

- ### Application Interaction:

  - Students should understand how their application interacts with the Payment Gateway. For simple applications, users are redirected to a Gateway's webpage for credit card processing. More complex applications, known as third-party applications, securely pass credit card information to the Gateway through an API without storing it on the application server.

- ### Validation, Refunds, and Settlement:

  - If a customer's credit card is declined, a generic error message is usually displayed for security reasons. However, the Gateway and third-party applications may provide more specific failure information for management purposes. Successful transactions result in order numbers for reference and safer refunds. It's essential to note that funds don't appear in your bank immediately; Settlement, managed by the Merchant Account, takes several business days.

- ### Fees:

  = The reading emphasizes the importance of understanding fees associated with payment processing. Merchant Accounts typically have setup fees, monthly fees, and per transaction fees, with the Percentage Fee (usually 2.00-3.00% for MasterCard/Visa) being a significant cost factor. Payment Gateways and Internet Merchant Accounts also have setup fees, monthly fees, and per transaction fees, but these can vary.