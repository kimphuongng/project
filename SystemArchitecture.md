# System architecture:

## High-level view of the system: 
 
 ![alt text](http://users.metropolia.fi/~kimn/Software%20Engineering/High-levelOverview.png "High-level") 
 
 
## Main modules and their function represented: 
* ###Server: 
- Receive and store users data and setting from smartphone
- Processing the locations
- Matching people with similar interests
- Allow Admin PC to change setting and send broad-cast notifications
 
* ###Indoor Positioning: 
- Inform the smartphone its location

* ###Smartphone:
- Receive location from Indoor Positioning 
- Send its location to server
- Receive data from server
- Allow user to input setting and information
- Send user’s setting and information to server
- Push notification

* ###Admin PC:
- Allow Administrator to interact with Server

* ###Administrator:
- In charge of server setting
- Send broad-cast notification

* ###Student:
- Received data presented by the Smartphone
- Change personal information and setting 
