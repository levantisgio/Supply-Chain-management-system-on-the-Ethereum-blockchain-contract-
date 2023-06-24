## Supply-Chain-management-system-on-the-Ethereum-blockchain-(contract)-

The "SupplyChain" contract is implemented in Solidity version 0.8.0.The contract includes various data structures and functions to track the lifecycle of products within the supply chain, manage participants' roles, and handle transactions.

Key Features:

Participants: The contract defines various roles in the supply chain, including the supplier, transporters, manufacturer, warehouse, distributor, and pharmacy.

Roles: Each participant is assigned a specific role, such as an administrator, logistics personnel, or inspector.

Product Tracking: The contract allows for the creation of new products, with each product having an ID, name, current owner, previous owners, courier, seller, status, departure date, expected arrival date, price, and delivery fee.

Product Lifecycle: Participants can ship, receive, and deliver products, which updates the product's status and transfers ownership to the next participant in the chain.

Payment and Delivery: When a product is delivered, the contract calculates the payment amount for the previous owner and the delivery fee. It ensures sufficient funds in the contract and facilitates payments to the previous owner, courier, and seller.

Product Cancellation: In case a product needs to be cancelled, the contract handles the cancellation process and facilitates the refund of the product price to the seller.

The contract provides transparency and traceability in the supply chain by leveraging the immutability and decentralized nature of the blockchain. It allows for secure and auditable product tracking, facilitates seamless transactions, and ensures proper payments throughout the supply chain process.
