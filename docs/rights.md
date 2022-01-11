# Roles and permissions

This describes the roles that exist in the application, and the rights each role has on each endpoint.

|                                           |       |SuperAdmin |Institution Admin          |Inviter                    |Guest                                      |
|---                                        |---    |---        |---                        |---                        |---                                        |
|/invite/?id=<br>Retrieve single invite     |GET    |Allow      |Limited to own Institution |Limited to own Institution |Only if the user is invited                |
|/invite/<br>Send an invite                 |POST   |Allow      |Limited to own Institution |Limited to own Institution | -                                         |
|/invite/<br>Update an invite               |PUT    |Allow      |Limited to own Institution |Limited to own Institution |Only update status if the user is invited  |
|/invite/<br>Revoke an invite               |DELETE |Allow      |Limited to own Institution |Limited to own Institution | -                                         |
|/role/?id=                                 |GET    |Allow      |Limited to own Institution |Limited to own Institution | -     |
|/role/                                     |POST   |Allow      |Limited to own Institution | -                         | -     |
|/role/                                     |PUT    |Allow      |Limited to own Institution | -                         | -     |
|/role/                                     |DELETE |Allow      |Limited to own Institution | -                         | -     |
|/roles/                                    |GET    |Allow      |Limited to own Institution |Limited to own Institution | -     |
|/user/?id=                                 |GET    |Allow      |Limited to own Institution |Limited to accepted invites|Only own information       |
|/user/                                     |POST   |Allow      |Limited to own Institution |Limited to accepted invites| -     |
|/user/                                     |PUT    |Allow      |Limited to own Institution |Limited to accepted invites|Only own information       |
|/user/                                     |DELETE |Allow      |Limited to own Institution | -                         | -     |
|/users/                                    |GET    |Allow      |Limited to own Institution |Limited to accepted invites| -     |
|/application/?id=                          |GET    |Allow      |Limited to own Institution |Limited to own Application |Only invited application   |
|/application/                              |POST   |Allow      |Limited to own Institution | -                         | -     |
|/application/                              |PUT    |Allow      |Limited to own Institution | -                         | -     |
|/application/                              |DELETE |Allow      |Limited to own Institution | -                         | -     |
|/applications/                             |GET    |Allow      |Limited to own Institution |Limited to own Application |Only invited application   |
