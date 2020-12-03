# Planning Document -- Zoom Standup Chatbot

## User flow

### Manager

`!standup-options`

`!standup-start`

`!standup-end`

`!standup-status`

`!standup-questions [add, remove, list]`

`!standup-reports [add, remove, list]`

## Classes

### Standup

* Manager
* reportChannel
* Reports[]
* Questions[]
* isWaiting
* timeStarted
* timerLength

### Question

* ID
* Question Text

### Report

* ID
* username
* answers


