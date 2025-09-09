**Microservices Architecture Assignment**
-----

This project illustrates a microservices architecture using Flask with 2 services : order and user.
Create a python virtual environment, install Flask and Requests and run the 2 services independently.

- ***User Service***: Manages user data.
- ***Order Service***: Manages orders and calls the User Service.
  
**Prerequisites**
---

***Create a virtual environment***

python -m venv myenv

***Activate virtual environment on windows***

myenv\Scripts\activate

***Install Flask***

pip install flask requests

**Output**
--

***Both the services running on different ports independently.***

![Architecture Diagram](order_service_run.png)
![Architecture Diagram2](user_service_run.png)

***Creating a User***

![Architecture Diagram3](create_user_3.png)

***Getting a User***

![Architecture Diagram4](get_user.png)

***Creating an Order***

![Architecture Diagram5](create_order.png)

***Getting an Order***

![Architecture Diagram6](get_order.png)





