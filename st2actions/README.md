# Introduction

Contains code for action runners. A new runner written for StackStorm would be added to st2actions/st2actions/runners. Also, this folder contains the code for worker node that scans RabbitMQ for incoming executions.

Notifier and results tracker are also part of this code base. Notifier is the component that sends notification triggers and action triggers at the end of action execution. Results tracker is an advanced async results querier for certain kind of runners like Mistral, where execution of a workflow is kicked off remotely and you have to poll the Mistral APIs to collect results.

Action Runner
=============

See: https://stackstorm.atlassian.net/wiki/display/STORM/Demo+-+ActionRunner
     https://stackstorm.atlassian.net/wiki/display/STORM/API+Design
     


