# OnePasswordLess

The site [OnePasswordLess](http://www.onepasswordless.com) is my weekend project. The project is to practise the latest ReactJs+Flux framework to see how fast we can deliver a WebApp using the latest Web framework tools in a short time.

## What is [www.onepasswordless.com](http://www.onepasswordless.com)?

The site is designed to help user to remind their account login info. We have so many online accounts and it is very easy we will forget the user name or password. However, we always use very similar username or password on different sites. So if we save a hint to the online account, we will be able to recall the login info easily.

The site has the following features:

1. Register the site without creating any account. You will have one username/password less to rememeber.
2. We send a link to your email to let you login. If you can receive the account recovery email to recover your account, why not directly login? Other site already assume your email account is mostly trusted, then why not directly login from the link to your email.
3. The login link is ensured to last only shortly after it is sent. If new request to login is sent, the old link will be expired. You can click the link to login only once. If clicking the link again, it will not login. You will have to require an access link again.
4. The site do not remember your account info unless you really want to. We will save only user name, or masked/hashed password. You can provide a hint to your account just for yourself to recall. If you save a hashed password, we will let you keep trying your password to find whether you can find the exact one. 

## Frameworks in [www.onepasswordless.com](http://www.onepasswordless.com)?

Mainly the whole WebApp is built on top of [Yeoman](http://yeoman.io/) + [generator-yeogurt](https://github.com/larsonjj/generator-yeogurt).

What I used in the development:

1. ReactJS + Flux
2. Sass
3. Bootstrap
4. MongoDB
5. NodeJs with modules express, passport, and mongoose etc.
6. Grunt

