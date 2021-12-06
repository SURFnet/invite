# Invite

## Intro

This application provides an API to send email invites to users.
Once the invite is accepted, the new user roles can be sent to external systems
by [SCIM](https://datatracker.ietf.org/doc/html/rfc7643#section-4.1) or email
(ticketing system). Also a
[VOOT](https://wiki.geant.org/display/gn3pjra3/VOOT+specifications) provider is
available for publishing the users' memberships.

To test and demonstrate the application, an example client application is available.

## Documentation

- [API documentation](./api/)
- [Architecture design](./archi/?view=00685569-37a2-4756-b7b7-6f79dc6bdbd1)
- [Roles & permissions](./rights.md)
- [Code - server](https://github.com/SURFnet/invite-server)
- [Code - UI](https://github.com/SURFnet/invite-ui)
