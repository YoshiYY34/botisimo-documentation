# $(winner)
Resolve the username as a mention of a random user currently online in the channel

## Usage
$(winner `[minutes=10]` `[keyword=]`)

## Example
    The winners is $(winner 5 enter)!

Outputs a randomly selected user who is online and sent the message "enter" in the last 5 minutes. The keyword is case sensitive.

`!winner` -> `The winner is @gary!`