---
title: "Experience"
bg: buzzgold60  #defined in _config.yml, can use html color like '#0fbfcf'
# fg: buzzgolf
color: black   #text color
# fa-icon: cloud-download
---

<div class="container">
    <div class="row">
    <h2 style="font-weight: bold;letter-spacing: -.8px;">Experience</h2>
    </div>
</div>

Software Engineer<br>
<strong>PayPay Corp.</strong><br>
Sep 2020 - Present<br>
<small>Tokyo, Japan</small><br>

- Built Alpakka Kafka application (akka stream integrated with Kafka) to solve faster producer and slow consumer problems by utilizing its flow control features (reactive stream with backpressure).
- Added complex Device List feature to sign-up, sign-in, and log-out APIs to handle user access information under different scenarios in the combination of user, device, client, and session parameters to detect account takeover.
- Improved Notification Center APIs to introduce DynamoDB TTL feature to the API user.
- Developed Push Notification System to send email/sms/otp, push messages to the app, and access internal and external APIs to accomplish tasks.

Used techniques: Spring Boot, OAuth 2.0, OIDC, Kafka, MySQL, Redis, AWS DynamoDB, Kibana, NewRelic, and Java

<hr style="border: solid #bfbfbf; border-width: 1px 0 0; ">

Software Engineer<br>
<strong>Rakuten</strong><br>
Oct 2018 - Aug 2020<br>
<small>Tokyo, Japan</small><br>

- Identified critical DB migration issues twice by tracing log and code from gateways to microservices, raised awareness concerning issues to the relevant developers.
- Built Kafka consumer applications as a base for multiple projects from the ground up to apply complex business logic on messages sent from different producers (internal systems and external vendors) and save into DB.
- Integrated trace context of multiple upstream (Kotlin and PHP) and downstream (Kotlin) applications written in different languages to allow distributed tracing.
- Developed multiple Gateways (Kotlin and PHP) and Microservices (PHP) at the same time to support different projects, which includes complex business logic handling, DB CRUD, email sending, JWT authentication, and etc.
- Utilized Change Data Capture techniques (MySQL binlog, Maxwell, Kafka) to synchronize data between MySQL and Couchbase (flattened ranged data into Couchbase to speed up searches).
- Rebuilt (unified) log format of applications actively to remove duplicated data, provide clear alert notification, save parsing scripts within ETL process by utilizing MDC and Logstash Logback Encoder (JSON layout).

Used techniques: Spring Boot, Laravel, Kafka, MySQL, Couchbase, TigerGraph, Kibana, Express.js, MongoDB, Kotlin, and PHP

<hr style="border: solid #bfbfbf; border-width: 1px 0 0; ">

Software Engineer<br>
<strong>TSMC</strong><br>
Feb 2017 - Jul 2018<br>
<small>Hsinchu, Taiwan</small><br>

Outlook Email Monitoring Service
- Created RESTful web services to control 40K employees’ outgoing email.
- Setup MS SQL Servers and built HA DB with Always-on Availability Group (master-slave/failover). Created SQL server jobs to notify failure, backup DB/transaction log and synchronize data between SQL servers.
- Created automated MS Windows Service to fetch and process data from Outlook Exchange server and save into DB. Enabled web services to read data fast from DB with acceptable stale read.
- Utilized Apache JMeter to perform stress testing on system and HP SiteScope to monitor service availability.
- Ran 240 test cases manually identified by the Legal department to ensure all scenarios are covered.

Company App Portal
- Built an Android app with Google Play-like features to browse, download, update, and comment on company apps.

Used techniques: ASP.Net Web API, C#, MS SQL Server, Apache JMeter, HP SiteScope, Java and Android



<!-- The source code for the *argon.js* framework, samples and documentation are all available on this github site, and use the Apache 2.0 Open Source License. 

The Argon4 Browser application is available for free on the iTunes App Store for iOS and the Google Play Store for Android.

<center><a href="https://itunes.apple.com/us/app/argon4/id1089308600?ls=1&mt=8"><img src="img/Download_on_the_App_Store_Badge_US-UK_135x40.svg"></a>

<a href="https://play.google.com/store/apps/details?id=edu.gatech.argon4"><img src="img/google-play-badge.png" style="height: 40px;"></a></center>

<p></p>
<em style=" font-size:smaller">Google Play and the Google Play logo are trademarks of Google Inc.  Apple and the Apple logo are trademarks of Apple Inc., registered in the U.S. and other countries. App Store is a service mark of Apple Inc., registered in the U.S. and other countries.</em> -->