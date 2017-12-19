# IBMMQ-Logs-Splunk
Splunk source type for IBM MQ error logs

## Overview

This is a Splunk source-type add-on to parse the fields present in IBM MQ error logs.


## Features

* Standard UI configuration via Splunk Manager
* Supplies dedicated IBM MQ source type for error logs
* Handles global and per-QMgr error logs
* Defined fields include the explanation and suggested action test lines


## Dependencies

* Splunk 7.1 (May work with other versions but not tested)
* IBM MQ server v8.0 (May work with other versions but not tested)
 

## Setup

* Add stanzas to props.conf and transforms.conf in [splunk-home]/etc/system/local
* Restart Splunk


## DISCLAIMER
You are free to use this code in any way you like subject to the terms of the Splunk and IBM products with which you use it. I make no representations about the suitability of this software for any purpose. It is provided "AS-IS" without warranty of any kind, either express or implied. 
