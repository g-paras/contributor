# Fake Contributors 😂🤣

> I created this repo just for fun

<br />

## How I got these contributors ?

I read [this post](https://dev.to/martiliones/how-i-got-linus-torvalds-in-my-contributors-on-github-3k4g) on [dev.to](https://dev.to), and then followed these steps.

<br />

## 2 Simple steps to get contributors

__Step 1.__

Use this api to retrieve email address of the user

```
https://api.github.com/users/<username>/events/public
```

__Step 2.__

Make commit and push changes.

```
git -c user.name='<username>' -c user.email='<user-email>' commit -m "Commit Message"
```