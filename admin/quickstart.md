# Quick start for server administrators

Feniks is managed trough a modern web interface. To get started visit [feniksbot.com](https://feniksbot.com)
and add Feniks from there. When Feniks has joined your Discord server log in to the [dashboard](https://feniksbot.com).

?> Feniks is managed trough a web interface available at [feniksbot.com](https://feniksbot.com).

## Basic configuration
Although Feniks will start to award XP out of the box you will need to configure some bare minimums in order for it
to actually provide value to your users.

!> Before configuring an announcement channel and an audit channel Feniks will complain when running the `/level` and the `/scores` command.

## How to configure Feniks

1. Head over to [feniksbot.com/admin](feniksbot.com/admin)
2. Click the *Login with Discord* button
3. Click the *Authorize* button
4. Below the guild you want to configure press *edit settings*

!> The dashboard will list all your servers, even if Feniks is not invited to them

## Permissions

Feniks will ask for the `administrator` permission by default. The reason
for this is to be able to access all channels and minimize the effort required
to get started using Feniks.

### Removing the administrator Permissions

If you want you can remove the administrator permission from the `Feniks` role.
If you do, be sure to give it the `Manage Roles` permission if you want to
be able assign roles when users level up.

![Administrator permission](https://docs.feniksbot.com/img/administrator-permisssion.png)
![Administrator permission](https://docs.feniksbot.com/img/manage-roles-permission.png)

!> Feniks will only be able to award XP for messages in channels it has access to.
