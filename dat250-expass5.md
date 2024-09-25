## Technical problems that you encountered during installation and use of MongoDB and how you resolved
First of all the installation of MongoDB was somewhat hard to understand. I had a hard time understanding how we were supposed to install it and why we had to validate the installation package. However, I managed to overcome these issues, as seen below. 

## Screenshots for:

#### The correct validation of the installation package (https://docs.mongodb.com/manual/tutorial/verify-mongodb-packages/)
<img width="395" alt="image" src="https://github.com/user-attachments/assets/7a7270d8-6b6b-4066-b9f1-8e82c4996933">


#### Relevant results obtained during Experiment 1 (it is not necessary to put a single screenshot on each substep, but at least one significant from each CRUD operation).

### Create
<img width="366" alt="image" src="https://github.com/user-attachments/assets/26b40e94-4e50-4f83-848e-ca513db4fd96">

### Read

SELECT * FROM inventory;

<img width="367" alt="image" src="https://github.com/user-attachments/assets/a2bd6f88-baf7-4bc2-aa17-3f7a2efff7a7">

SELECT * FROM inventory WHERE qty = 25;

<img width="343" alt="image" src="https://github.com/user-attachments/assets/55cfea96-2e73-4440-bb99-6034d186499a">

### Update
<img width="360" alt="image" src="https://github.com/user-attachments/assets/96ef4118-8151-45a8-80a0-1cb8cbaef3d4">


### Delete
<img width="405" alt="image" src="https://github.com/user-attachments/assets/aa802856-50e2-4c25-81ea-f5682bf50e31">

### Bulk operation

<img width="679" alt="image" src="https://github.com/user-attachments/assets/a84cfa61-dad6-4cd4-86ec-ec226d4d6643">

#### Experiment 2 example working and the additional Map-reduce operation (and its result) developed by each of you.

Example 1

<img width="416" alt="image" src="https://github.com/user-attachments/assets/23533867-a271-4636-bcd1-92f5212b6f6d">

Example 2

<img width="466" alt="image" src="https://github.com/user-attachments/assets/6dd58bb9-f1a9-4452-8d67-a9a9ce27deb8">


My own additions:
 Example 1 (Avg price per customer):
 
  <img width="533" alt="image" src="https://github.com/user-attachments/assets/ba670c15-4e54-4353-a4f3-694dd16ebb01">

 
 Example 2 (Add price):

 <img width="546" alt="image" src="https://github.com/user-attachments/assets/fd5fe189-ad45-4d88-a9b0-159260a8eab6">



## Reason about why your implemented Map-reduce operation in Experiment 2 is useful and interpret the collection obtained.
The first examples additional operation will show what one costumer uses in average on the store, which can be fun to see the statistics of, also to see which costumer buys the more expensive items per usual while which other buys the cheaper ones. This can be good insight for the customer and the business keeping these records. Although this shouldn’t be viewed solely in isolation to get the full image of the buyers history and tendencies.  

As for the second example, price was added to not only showcase the quantity, count and avarage for each item but also it´s costs. 
## Any pending issues with this assignment which you did not manage to solve
No pending issues to my knowledge left.
