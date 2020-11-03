## Assignment7_Week43_EIP_ReadingTask
**[Source Link](https://www.enterpriseintegrationpatterns.com/docs/EnterpriseIntegrationPatterns_HohpeWoolf_ch03.pdf)**  

**Messaging System**  
System that runs between application asynchronously that could send messages between applications based on basic concepts.

**Message Channel**  
A message channel is a part of message system, where an application act as sender and another application act as receiver.

**Message**   
A message is content with a header and a body to send in message system, an example of this is a SOAP message.

**Pipeline processing**  
This is when a message is sent to a channel and its operation is done and ready for a new message. This make it possible to process more messages at same time.

**Parallel processing**  
This process makes it possible to create instances of messages but is limited by waiting for the slowest process to be finished.

**Message router**  
A message router is used to only concern about a message destination and could be used to control the rounting of a message.

**Message endpoint**  
This is message endpoint code that makes data into a message and send to a message channel.

**Message translation**  
When content of a message requires some additional changes based on format input file, example XML and CSV.

**Publish-Subscribe**  
When destination can choose which messages, they want to get when published.

**Point-to-Point**  
This is when a message is ensured to be delivered to a destination directly.
  

