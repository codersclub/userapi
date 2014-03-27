CodersClub User API
===================

User API for all the CodersClub resources

CodersClub **User API** is an application interface library designed for integration of various CodersClub applications and resources. The goal of User API is to store users info in a single place and provide the same authentication for all our services. This API enables to access/manage all the user's info in all the applications of our community.

![userapi](http://github.com/codersclub/userapi/blob/master/userapi.png?raw=true)

**User API** offers 2 access methods:
  - Direct Database Access for local applications (hosted at the same server as the API)
  - Remote HTTP RESTful Access for remote applications

**User API** contains the next functional modules:
  - Applications (Handle applications integrated with the User API)
  - Users (Unified Authentication & Profile Management for all the users)
  - Private Messages (Handle PM for all the users and all the applications)
  - Feed (Handle all the user news feeds)
  - Friends (Handle all the user friens)
  - Mail (Handle all the email messages)
  - Cache (Caching the most used data)
  - Cron (Task sheduler)

**User API** consists of 3 parts:
  - Client side library
  - Server side service
  - Server side admin-panel
