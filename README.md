# Whitelist

This is a very simple PHP Whitelist Library.

## Why use a WhiteList?
Recently I had the amazing idea to simply block URL's that I don't want, after all I am the owner of the Website and also responsible for links that are on my website.
So I integrated this class into my BBCode Parser and all of the sudden people were unable to spam links unless I had whitelisted the websites.

I personally use a simple MySQL table and a daily cron to update the file (mysql is only used to manage data).

I don't claim that this is the best solution to spam. But I am sick of Captcha's, And let's be honest, this is your website, you shouldn't have to clean up afterwards. Just start with trusted sites (google/facebook/etc) and add as you go along. People can try and spam all they want. It will not work.
And without a backlink, it is useless to them. And they will eventually stop trying on your website. 

## Why use this class?
Recently I decide to OpenSource this for everyone to build upon. A Whitelisting solution in PHP was non-existant when I needed one , so I decided to share my very simple solution.

This is released under the UnLicense. So do whatever you want with it.
You are also free to contribute if you want.

### Notes:
- It is a Whitelisting class, not a AntiSpam Class. Even though that's what I use my whitelist for.
- The Whitelist seperates items read from a file by newlines.