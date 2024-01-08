# Functor Factory Micro-Services Example

This is an example of a small platform meant to demo micro-service architecture
in different programming languages and frameworks. Each sub-directory
re-implements the same general design, but tailored to the particular language
and framework it is demonstrating.

Imagine a business that needs to track their inventory. They need a platform
with three user roles: 

1) Someone needs to sell their inventory to customers and this person needs to
be able to see how much of each item they have in stock. They need to be able to
create an order when they sell something and receive a notification when the
stock starts to run low. After getting that notification, they need to submit a
purchase order and track that order's status while waiting for the new delivery
to come in.

2) Someone needs to process and approve purchase orders. They need to receive a
notification when a new purchase order is created and be able to accept or
reject it. After accepting an order, they need to be able to track the status of
the delivery.

3) Finally, someone needs to manage user accounts, assign user roles, and
monitor all orders, notifications, and inventory throughout the system.
s
