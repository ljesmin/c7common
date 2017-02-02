# Common role for Centos hosts

## Description

This role installs commonly needed utilities, sets hostname, mail hostname, 
forward for root mail and starts or stops firewalld as needed.

## Variables

|type|name|default|desription|
|----|----|-------|----------|
|string|shortname|none|String shown in prompt|
|string|mail_hostname|none|Server name for outgoing mail|
|string|server_hostname|none|Server hostname|
|string|rootmail|none|Mail address, destination for root mail|
|boolean|start_firewalld|true|If firewalld should be started|
