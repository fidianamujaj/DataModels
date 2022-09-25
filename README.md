# DataModels
Data models created, altered and modernized in my __CSCI381: Data Modeling__ class

## Documentation

The following sections show a modernized and naturalized version of eMovies to eStreaming. The entity and attribute names have been case standardized. Aditionally, they have been updated, removed or added from the initial eMovies model to result in the ability of a customer to subscribe to movies.

### Additions

* Subscription
* Credit Card
* Check
* Epay
* Address
* City
* State
* Director
* Actor
* Cast

### Updates

- All tables

### Deletions

- Cust_Credit (No longer necessary since incorportated payment method)
- PaymentMethod that was earlier added. In the updated version I used a discriminant attribute in the Payment table instead of a PaymentMethod table.

# Final Models

## Conceptual Model

![ConceptualModelUpdated](https://user-images.githubusercontent.com/27741728/192130820-943fd198-3aec-49d4-86f0-98b0cf416a58.PNG)

## Logical Model

![LogicalModelUpdated](https://user-images.githubusercontent.com/27741728/192130825-7680defd-2a68-4d84-87af-7f4deb5a76cd.PNG)

## Physical Model

![PhysicalModelUpdated](https://user-images.githubusercontent.com/27741728/192130830-3d1cd9bf-6f96-4207-b138-75ce86f6bffd.PNG)






