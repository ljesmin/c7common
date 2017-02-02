# Common role for Centos hosts

## Description

This role installs commonly needed utilities, sets hostname, mail hostname, 
forward for root mail and starts or stops firewalld as needed.

## Variables

|type|name|default|required|desription|
|----|----|-------|--------|----------|
|string|shortname|undefined|no|String shown in prompt|
|string|mail_hostname|undefined|no|Server name for outgoing mail|
|string|server_hostname|undefined|no|Server hostname|
|string|rootmail|undefined|no|Mail address, destination for root mail|
|boolean|start_firewalld|true|no|If firewalld should be started|
