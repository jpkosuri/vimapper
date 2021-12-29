### Visually map and transfrom one json/xml to another json/xml format. And, generate mappers, source and destination pojos.

### from

> {user : { userName : "John", userID: "123"}}
### to
> {customer: { customerName : "John", customerID: "123"}}

### Output
```
mappers/UserCustomerMapper.java
from/User.java
to/Customer.java
```
