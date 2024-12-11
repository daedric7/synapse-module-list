[Super Invitation flow for Synapse Matrix Homeserver](https://github.com/acterglobal/synapse-super-invites)
> Provides extended support for users to invite other users to rooms via an invitation token

[synapse-simple-antispam](https://github.com/t2bot/synapse-simple-antispam)
> A simple spam checker module for Synapse to block invites from unwanted homeservers

[mjolnir.Module](https://github.com/matrix-org/mjolnir/blob/main/docs/synapse_module.md)
> use your ban lists (or someone else's) on your server to affect all of your users

[Synapse User Restrictions Module](https://github.com/matrix-org/synapse-user-restrictions)
> This module allows restricting users, that match given regular expressions, from performing actions such as creating rooms or sending invites.

[Auto-accept invites](https://github.com/matrix-org/synapse-auto-accept-invite)
> Synapse module to automatically accept invites.
> Compatible with Synapse v1.84.0 and later.

[Matrix-Synapse Shielded User Invites Module](https://github.com/lovelaced/synapse-mayinvite)
> This module is a matrix-synapse server module that blocks certain users from receiving invites from users on other homeservers. This is useful if you have a specific list of users that should not receive invites from users on other homeservers, for example if you want to protect the privacy of these users.

[Matrix encryption disabler](https://github.com/digitalentity/matrix_encryption_disabler)
> This Pluggable Module disables end-to-end encryption in a self-hosted Synapse servers. It works by stripping out requests for encryption from newly created rooms, patching power levels to prevent users from enabling encryption and additionally filtering out events for enabling E2EE on already existing rooms if a user or a room belongs to a configured list of servers.

[FEZ Chat Modules](https://heptapod.host/intevation/fac/synapse-modules)
> Repository of multiple modules:
> * *Message Type Filter*
> * *Restrict Direct Messages* (restricting event types and number of members in direct message rooms)
> * *Restrict Room Creation* for parent-less rootms to synapse admins
> * *Static Account Data* for user accounts (useful for stickerpicker deployment to all users)
> * Additional API endpoints for public spaces

[Synapse Guest Module](https://github.com/nordeck/element-web-modules/blob/main/packages/synapse-guest-module/README.md)
> A pluggable synapse module to restrict the actions of guests.
> Features:
> * Provides an endpoint that creates temporary users with a same pattern (default: guest-[randomstring]).

[synapse-invite-checker](https://github.com/famedly/synapse-invite-checker)
> Synapse Invite Checker is a synapse module to restrict invites on a homeserver according to the rules required by Gematik in a TIM federation.

> * The temporary users have a mandatory displayname suffix (default:  (Guest)) that they can't remove from their profile.
> * The temporary users are limited in what they can do (examples: create room, invite users).
> * The temporary users won't be returned by the user directory search results.
> * The temporary users are disabled after an expiration timeout (default: 24 hours).
