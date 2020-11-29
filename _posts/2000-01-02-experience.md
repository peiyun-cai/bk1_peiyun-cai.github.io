---
title: "Work Experience"
bg: white-2
color: black
---

<div class="container">
  <div class="row">
    <div class="half column">
      <h3 class="left">September 2020 - Present</h3>
    </div>
    <div class="half column">
      <h3 class="right"><strong>PayPay Corp. </strong>Software Enginner</h3>
      <h4 class="right">Tokyo, Japan</h4>
    </div>
  </div>
</div>

- Optimized risk payload and kafka event publish feature for fraud check
  - avoid account take over and reduce damage when happened
- Opted device list feature to current SignUp, SignIn, Token Grant Flow 
  - act flexibly to adopt new design after adjustment
  - relate user and device login info, ex, user identity, device unique id, device model, login time, ip address, client id, token, 2fa and etc
  - support different grant type: password, yahoo, etc
  - activate 2fa mechanism by introducing otp within sign-up, sign-up, link external service.
- Migrated Push Notification System (Sms, Email, and Push) to new System (written in DDD architecture)
  - sms password reset, otp, sms delivery history, check MSN contract validity
  - kafka producer and sender application
- Improved Notification System to be able to set DynamoDB archiving TTL of notification data

-------------------------

<div class="container">
  <div class="row">
    <div class="half column">
      <h3 class="left">October 2018 - August 2020</h3>
    </div>
    <div class="half column">
      <h3 class="right"><strong>Rakuten Inc. </strong>Software Enginner</h3>
      <h4 class="right">Tokyo, Japan</h4>
    </div>
  </div>
</div>

- Responsiblely developed new Gateway System(kafka consumer, Java) to consume message from both Legacy(PHP) and New System(Java)
  - vendor system=>new gateway API produce message=>kafka=>consumer apply business logic and save to microservie
  - internal system=>legacy gateway API produce message=>
  - developed consumer and microservices
  - integrated upstream(Java, Php) and downstream(Java) application having the same trace context 
  - support data synchronization to Microservice

- Developed microservices with event-driven system to synchroize Golf Course 
between Vendor System, Golf Booking websites, and Golf course owner
  - supported Gateway access each microservice
  - acted as kafka consumer to synchronize and integrate data between MySQL and CouchDB
  - published event to Kafka for asychonous email sending
  - acted as kafka consumer for failure microservice update event and rollback data

- Developed gateway to support front-end authorization and authentication
  - applied business logic and save/delete data to DB through microservice  
  - published failure microservice event to kafka

- Utilized Change Data capture, MaxWell to capture binglog change, and finally Synchronize data to CouchDataBase 
- Developed Gateway to support Front-end application
  - Handled authrization and authentication
  - Handled business logic and communicated between front-end and back-end 
  - Published microserice failure event to kafka for rollback

- Optimized gateway application log4j format to be readable in alert, kibana and easyily processed by ELK stack 
- Quickly indentified migration issues by tracing gateway and microservice system
- Fixed Jacoco Code coverage problems resulted from PowerMock (which load class from disk not probed class)

-------------------------

<div class="container">
  <div class="row">
    <div class="half column">
      <h3 class="left">February 2017 - July 2018</h3>
    </div>
    <div class="half column">
      <h3 class="right"><strong>TSMC Inc. </strong>Software Enginner</h3>
      <h4 class="right">Hsinchu, Taiwan</h4>
    </div>
  </div>
</div>

- Created Email Monitoring Service to Control 40k employees' outgoing email
  - Created RESTful web services to control 40K employees’ outgoing email. Deployed on servers located at different sites and applied Load Balancer to create highly available service.
  - Setup MS SQL Servers and built HA with Always-on Availability Group (automatic failover). Created SQL server jobs to notify failure, backup DB/transaction log and synchronize data between SQL servers.
  - Created automated MS Windows Service to get required data from Outlook Exchange server and store in DB. Enabled web services to read data fast from DB with acceptable stale read.
  - Utilized Apache JMeter to perform stress testing on web servers and HP SiteScope to monitor availability of the services.
  - Worked with the frontend Outlook Add-ins developer to discuss system API interface and cooperated passing 240 test
  cases successfully identified by Legal department.
- Company App Portal
  - Fast built an Android app with Google Play-like features to browse, download, update, and comment on company apps within one and half month
