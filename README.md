# Poe_AI
Deep learning twitter bot 

## Description
Made using python3, tensorflow and the latest reddit comments from 2018-03 to 2018-05
Intended to release into twitter this bot is a experimental practice for neural network implementation


## Setup
Training is done by using the reddit comments database from:
http://files.pushshift.io

the database is first formated from JSON into a SQL file and uses parent comments and top reply comments
then it is fed through a Neural Network using tensorflow

## Future improvement

Improvement are planned to scale the bot up by feeding it more and more data.
In the future more reddit comments will be used and perhaps their API as well.
On top of that twitter API may be used to feed more data and produce more natural responses.
voice implementation is also planned.

## License
This project is licensed under the MIT License - see the License.md file for details
