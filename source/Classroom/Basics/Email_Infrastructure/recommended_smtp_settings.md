---
seo:
  title: Recommended SMTP settings
  description: Recommended SMTP settings
  keywords: password, smtpapi, settings, ports, credentials, authentication, username, integration, smtp, auth, server, port, relay, external, setup, smtp.sendgrid.net
title: Recommended SMTP settings
weight: 0
layout: page
zendesk_id: 200328026
navigation:
  show: true
---

#**Integrate with Sendgrid using SMTP**

- Change your SMTP authentication username and password to your **SendGrid username and password,** or set up a [Multiple Credential](https://sendgrid.com/docs/User_Guide/multiple_credentials.html) with the "MAIL" permission enabled. 
- Set the server host to **smtp.sendgrid.net.** This setting can sometimes be referred to as the external SMTP server, or relay, by some programs and services.

##**Ports**

- Use port **25**, **2525**, or **587** for unencrypted / [TLS](https://sendgrid.com/docs/Classroom/Basics/Email_Infrastructure/ssl_vs_tls.html) connections
- Use port **465** for [SSL](https://sendgrid.com/docs/Classroom/Basics/Email_Infrastructure/ssl_vs_tls.html) connections

**We recommend using port 587** to avoid potential rate limiting. 587 is also the least likely to be blocked by default corporate and residential ISP network settings. 

When using SMTP, You can send 100 messages per SMTP connection at a time, and open up to 10 concurrent connections from a single server at a time.

For more information on how to integrate with Sendgrid, check out [our Integrate page.](https://sendgrid.com/docs/Integrate/index.html)
