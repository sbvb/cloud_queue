# cloud_queue
This is a cloud-mobile (SOA_MC) system to implement an electronic queue for the customer's customer

## Actors

* customer (e.g. restaurant)
* user (e.g. restaurant's customer)
* system

## Main use cases

* The customer (e.g. restaurant) register's itself
* The customer manages the queue (active/inactive)
* the user (e.g. the restaurant's customer) requests entering the restaurant queue
The restaurant's customer pays something for the privilege of entering the queue.
If he/she actually becomes a restaurant customer, the price paid becomes a discount.
If he/she does not show to restaurant at time of being first in queue, the system drops it, and moves the queue.
* system receives payment from user
* user can see his/her balance on system
* system estimates time to be the first in line
* system allows option of customer permit user enter queue only
if sufficiently close geographically

