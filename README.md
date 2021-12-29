### Visually map and transfrom one(source) json/xml/yaml to another(destination). And, generate mappers, source and destination pojos.

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
