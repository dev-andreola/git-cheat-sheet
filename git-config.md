<img src="assets/gitcs-main-header.jpg" align="center"/>

<br>

# Git Configuration

First of all, you need to fill in your username and personal email configuration to identify your changes when working on projects with other collaborators.

## Username

You can configure your username as follows:

```
git config --global user.name "your-username"
```

## Email

And to configure your email, it’s like this:

```
git config --global user.email "your@email.com"
```

<hr>

## Verification

To make sure that your settings is saved and everything is good to go put:

```
git config --list
```

It is going to list all of your settings. You can find the **user.name** and **user.email** values at the bottom.

Or you can use directly like this:

```
git config user.name
git config user.email
```
