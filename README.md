# GPT Message Tracker

This Bash script helps you track your ChatGPT usage.

To keep track, simply run `gpt` whenever you send a message. To see how many message you have left, run `gpt ?`.

Requests will automatically become available again after the cool-off period. The current default message limit and cool-off period are 25 messages and 3 hours, respectively.

## Usage
```
gpt                - Record that you used a message
gpt ?              - Display the number of remaining messages
gpt when [number]  - Display when additional messages will become available
gpt undo           - Remove the most recent message, in case you record one by accident
gpt hours [number] - Display or set the cool-off period
gpt limit [number] - Display or set the message limit
```
