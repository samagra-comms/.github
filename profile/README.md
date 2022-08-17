UCI is created with a vision to make the conversation flow creation configurable to a level, that it can be done by program owners, without the intervention of any engineers at all. At the same time, it also envisions reducing the redundant coding required for enabling the same business logic for different channels. 

UCI aims to democratize the use of different communication channels such as WhatsApp, Telegram, SMS, email and more across all governance use cases.

![image](https://user-images.githubusercontent.com/25716415/185061819-b180e0fd-bd6d-4bc3-a65e-0a9041055164.png)

UCI's architecture has created an abstraction layer between the Logic and the communication channels (WhatsApp, SMS, etc) and various providers (Like Gupshup, Twilio, etc.). UCI uses an adapter-based abstraction layer. An adapter has to be created for every channel+provider that is to be used with UCI. Once contributed, it is available for everyone in the community to leverage.

![image](https://user-images.githubusercontent.com/25716415/185061964-ecb34658-345a-432a-a8ec-821db0f396b0.png)

Read more about UCI [uci.sunbird.org](https://uci.sunbird.org/)
