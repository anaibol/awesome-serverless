# Awesome Serverless
#### A curated list of awesome services, solutions and resources for serverless / nobackend applications.
<img src="http://oi66.tinypic.com/jggm6f.jpg" align="right" height=300>

### Table of contents

- [What is serverless Computing?](#what-is-serverless-computing)
- [All in one solutions](#all-in-one-solutions)
- [Hosting and code execution in the cloud](#hosting-and-code-execution-in-the-cloud)
- [Isomorphic Engines](#isomorphic-engines)
- [Frameworks](#frameworks)
- [Authentication and authorization](#authentication-and-authorization)
- [Payments](#payments)
- [eCommerce](#ecommerce)
- [Forms](#forms)
- [Image management and File storage](#image-management-and-file-storage)
- [SMS sending](#sms-sensing)
- [Push notifications](#push-notifications)
- [Email sending and newsletters](#email-sending-and-newsletters)
- [Databases](#databases)
- [Others](#others)
- [Related artices](#related-articles)
- [Books](#books)


### What is serverless computing?

The phrase “serverless” doesn’t mean servers are no longer involved. It simply means that developers no longer have to think "that much" about them. Computing resources get used as services without having to manage around physical capacities or limits.

Let's take for example AWS Lambda. "Lambda allows you to NOT think about servers. Which means you no longer have to deal with over/under capacity, deployments, scaling and fault tolerance, OS or language updates, metrics, and logging."

https://www.quora.com/What-is-serverless-computing

### All in one solutions
* [Firebase](https://www.firebase.com/) - Realtime database, authentication, hosting. A powerful platform for your mobile or web application.
* [Backendless](https://backendless.com/) - Realtime database, authentication, hosting.
* [Stamplay](https://stamplay.com/) - "IFTTT For Back-End Development".
* [Kinvey](http://www.kinvey.com/) - Build your digital business faster with mobile Backend as a Service.
* [Syncano](https://syncano.io/) - An all-in-one platform to create realtime apps without a server.
* [Hoodie](http://hood.ie/) - Hoodie is a complete backend for your apps: develop your frontend code.

### Hosting and code execution in the cloud
* [Amazon Lamda](https://aws.amazon.com/lambda/) - Run code without thinking about servers. Pay for only the compute time you consume.
* [Google Cloud Functions](https://cloud.google.com/functions/docs) - Lightweight, event-based, asynchronous compute solution that allows you to create small, single-purpose functions that respond to cloud events without the need to manage a server or a runtime environment.
* [Azure Functions](https://azure.microsoft.com/en-us/services/functions/) - Listen and react to events across your stack.
* [IBM OpenWhisk](https://developer.ibm.com/openwhisk/) - Distributed compute service to execute application logic in response to events.
* [iron.io](https://www.iron.io/platform/ironworker/) - Isolates code and dependencies of individual tasks so they can be processed on demand.
* [weblab.io](https://weblab.io/) - Microservices at your fingertips.
* [Peer5](https://www.peer5.com/) - The serverless CDN. Limitless, affordable video delivery. More traffic means a stronger network.
* [Auth0 Webtasks](https://webtask.io/) - Run code with an HTTP call. No provisioning. No deployment.
* [Webscripts](https://www.webscript.io/) - Scripting on the web.
* [APItools](https://www.apitools.com/).
* [Surge](http://surge.sh/) - Deploy static sites from the command line.
* [Netlify](https://netlify.com/) - Generate & deploy static sites from git repositories.
* [Effe](https://github.com/siscia/effe) - a simple Open Source building block to emulate AWS Lambda.
* [Lever OS](https://github.com/leveros/leveros) - Serverless + Microservices = ♥
* [Now](https://zeit.co/now) - realtime node.js deployments

### Isomorphic Engines
* [lycheeJS](http://lycheejs.org) - Isomorphic adapters allow peer-to-peer event-graphed WebSockets and HTTP1.1, SPDY and HTTP2.0 sockets for node, node-sdl, html, html-nwjs and html-webview (both native and embedded).

### Frameworks
* [Serverless Framework](http://www.serverless.com/) - Build and maintain web, mobile and IoT applications running on AWS Lambda and API Gateway (formerly known as JAWS).
* [Apex](http://apex.run/) - Minimal AWS Lambda function manager with Go support.
* [Zappa](https://github.com/Miserlou/Zappa) - Serverless Python WSGI with AWS Lambda + API Gateway.
* [ClaudiaJS](https://github.com/claudiajs/claudia/) - Deploy Node.js microservices to AWS easily.
* [DEEP](https://github.com/MitocGroup/deep-framework) - Full-stack Web Framework for Cloud-Native Applications and Platforms using Microservices Architecture.
* [Sparta](http://gosparta.io/) - A framework that transforms a Go application into an AWS Lambda powered microservice.
* [Kappa](https://github.com/garnaat/kappa) - a command line tool that (hopefully) makes it easier to deploy, update, and test functions for AWS Lambda.

### Authentication and authorization
* [Auth0](https://auth0.com/) - Single Sign On & Token Based Authentication.
* [Stormpath](https://stormpath.com/) - User Identity API.
* (also [Firebase](https://firebase.com/).

### Payments
* https://github.com/auth0/webtask-scripts/tree/master/stripe
* [serverless-stripe-webhook](https://github.com/eahefnawy/serverless-stripe-webhook) - Serverless Module that creates a webhook for Stripe

### eCommerce
* [Snipcart](https://snipcart.com).
* [CommerceJS](http://commercejs.com/).

### Forms
* [Formspree](https://formspree.io/) - Functional HTML forms.
* [FormKeep](https://formkeep.com/) - Form endpoints for designers and developers. No iframes, JavaScript embeds, or CSS overrides.
* [Tectite FormMail](http://www.tectite.com/).
* [FormAssembly](http://www.formassembly.com/).
* [Google Forms](https://docs.google.com/forms/).

### Image management and File storage
* [Filestack](https://www.filestack.com/) - Image management system with Filestack - upload files, transform images, videos, and documents, store content and deliver fast via CDN.
* [Kloudless](https://kloudless.com/) - Integrate with one, universal API and connect to many file storage and CRM services.
* [Uploadcare](https://uploadcare.com/) - HTML5 widget, API to manage files in cloud storage, smart and fast CDN to deliver them to your end users. Crop, resize and transform uploaded images using URL commands.

### Realtime
* [Pusher](https://pusher.com/).
* [Pubnub](https://www.pubnub.com/).

### Email sending and newsletters
* [lambda-mailer](https://github.com/eahefnawy/lambda-mailer) - AWS Lambda for sending emails.
* [serverless-mailer](https://github.com/eahefnawy/serverless-mailer) - Serverless Module for sending emails.


### SMS sending
  * [serverless-twilio](https://github.com/eahefnawy/serverless-twilio) - Serverless Module to send SMS via twilio.

### Push notifications
* [Ionic Push](https://apps.ionic.io/landing/push).
* [Pushover](https://pushover.net/) Notifications for Android, iOS, and Desktop.
* [ZeroPush](https://zeropush.com) Transactional Push Notifications for Developers.
* [PushWizard](https://pushwizard.com/) Multi-platform Push Notification Service.
* [Pushed](https://pushed.co/) Send push notifications without developing your own app.
* [Plot Projects](http://www.plotprojects.com/) Geofencing push notifications.
* [XtremePush](https://xtremepush.com/) Web Push Notifications.
* [Push Apps](https://www.pushapps.mobi/) Push Notifications Enrichment Platform.

### Databases
* [Algolia](https://www.algolia.com/) - Hosted cloud search as a service.

### Others
* [remoteStorage](https://remotestorage.io/) - An open protocol for per-user storage.
* [Sockethub](http://sockethub.org/).
* [serverless-slack-webhook](https://github.com/eahefnawy/serverless-slack-webhook) - Serverless Module that creates a webhook for Slack.

### Related articles
* [AWS Lambda Microservices Architecture for Node.js](https://medium.com/getty-logs/a-aws-lambda-microservices-architecture-for-node-js-4513799101d4#.k99m6yvvz)
* [The Serverless Start-Up - Down With Servers!](http://highscalability.com/blog/2015/12/7/the-serverless-start-up-down-with-servers.html)
* [Microservices without the Servers](https://aws.amazon.com/blogs/compute/microservices-without-the-servers/)
* [A startup journey on AWS: from bare metal monolith to serverless microservices](https://medium.com/@benorama/a-startup-journey-on-aws-from-bare-metal-monolith-to-serverless-microservices-80231624fbd9)
* http://nobackend.org/
* https://unhosted.org/ unhosted web apps. freedom from web 2.0's monopoly platforms
* [Static Web Applications](https://staticapps.org/)
* [Serverlesscode](https://serverlesscode.com/)
* [Just Serverless](http://justserverless.com/blog)

### Books
* [Serverless](https://leanpub.com/serverless/) - Patterns of Modern Application Design Using Microservices (Amazon Web Services Edition).
* [Serverless Single Page Apps](https://pragprog.com/book/brapps/serverless-single-page-apps/) - The Pragmatic Bookshelf.
* [Learn Serverless](http://learnserverless.club) - Book about the [Serverless framework](http://serverless.com).


### License
[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

<!---
### Serverless Manifiesto
https://github.com/exis-io/Exis
https://www.imgix.com/
https://github.com/localytics/serverless-slackbot-scaffold
http://eng.localytics.com/serverless-slackbots-powered-by-aws/


http://www.imgix.com/ Real-time Image Processing. Resize, crop, and process images on the fly, simply by changing their URLs.
https://blitline.com/
Cloudinary
https://kraken.io
https://www.iron.io/
https://transloadit.com/
https://aws.amazon.com/elastictranscoder/
https://zencoder.com/en/
Now API
Instant serverless Node.JS deployments with an API.
https://zeit.co/
-->
