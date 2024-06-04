# 2fa
Two factor authentication project.

I find 2FA something interesting. So simple yet so effective, and I like how it's all offline and all done through logic.
As a simple way to explain 2FA to someone who doesn't understand, you get given a big string of characters (by the service you're setting up 2fa for). This string of characters may often be a QR code.
These long characters get saved to your device yet usually aren't accessible, but are combined with the current time (divided by 30 and rounded for a new code every 30 seconds) and then hashed (known for being secure and random) and fidled with to give you a unique 6 digit number.

MAKE SURE TO NEVER SHARE YOUR 2FA SECRET WITH OTHER PEOPLE. 2 THING SHOULD BE INVOLVED. THE SITE GIVING IT TO YOU AND THE TRUSTED APP YOU CHOOSE TO SET YOUR CODE UP IN.


I've added a feature so you can see your upcoming code and how long's left. 
While I've seen some apps show the duration left, I've never seen a single program show the next code which I think is such a cool feature.
I think it's nice to show upcoming codes as some apps only let you use each code once as a security measure, and when you're trying to something where you need to authenticate each time, it's nice to be able to pretype it out so the moment it's ready you can submit it.

Tried to make it presentable but this is python at the end of the day.

This is a poc - it doesn't save your secret which means you won't be able to use 2fa later on unless you made note of it and it's more of a demonstration rather than the next 2fa app!

