
# notifications
Assignment to create notification library using spring boot

# Background
Product Development Co. is developing an efficient notification library. Requirement are as follows:

Customers should be able to send messages using following channels:

 - Mail
 - SMS
 - Chat

The co. offers two types of packages one for standard customers and the other for enterprise ones
1. Standard Customers:
They get to choose one channel 

2. Enterprise users
The library will support all available types of channel

# Assignment - 1

Create an custom starter to support the above two scenarios

# Assignment - 2

1. Extend the notification library with a feature to send messages in a desired batch size. You can maintain a queue for this (maybe a simple List would work) For e.g. the library will only send messages once the batch size is achieved i.e. batch.size=list.size. Make the batch size feature configurable.

2. Create a health endpoint to check if the notification library is able to send messages to email channel. If not, then report as Health is down

3. Create an Info endpoint to expose the arbitrary details about the application /info endpoint. Probably it will good to display the maven coordinates.

4. Create a custom endpoint to show features & its status that are currently configured in the running application


