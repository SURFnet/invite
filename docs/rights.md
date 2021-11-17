# Roles and permissions

This describes the roles that exist in the application, and the rights each role has on each endpoint.

|                                           |       |SuperAdmin |RoleAdmin                  |Inviter                    |Guest                                      |
|---                                        |---    |---        |---                        |---                        |---                                        |
|/invite/?id=<br>Retrieve single invite     |GET    |Allow      |Limited to own Institution |Limited to own Application |Only if the user is invited                |
|/invite/<br>Send an invite                 |POST   |Allow      |Limited to own Institution |Limited to own Application | -                                         |
|/invite/<br>Update an invite               |PUT    |Allow      |Limited to own Institution |Limited to own Application |Only update status if the user is invited  |
|/invite/<br>Revoke an invite               |DELETE |Allow      |Limited to own Institution |Limited to own Application | -                                         |
|/role/?id=                                 |GET    |Allow      |                           |                           |       |
|/role/                                     |POST   |Allow      |                           |                           |       |
|/role/                                     |PUT    |Allow      |                           |                           |       |
|/role/                                     |DELETE |Allow      |                           |                           |       |
|/roles/                                    |GET    |Allow      |                           |                           |       |
|/user/?id=                                 |GET    |Allow      |                           |                           |       |
|/user/                                     |POST   |Allow      |                           |                           |       |
|/user/                                     |PUT    |Allow      |                           |                           |       |
|/user/                                     |DELETE |Allow      |                           |                           |       |
|/users/                                    |GET    |Allow      |                           |                           |       |
|/application/?id=                          |GET    |Allow      |                           |                           |       |
|/application/                              |POST   |Allow      |                           |                           |       |
|/application/                              |PUT    |Allow      |                           |                           |       |
|/application/                              |DELETE |Allow      |                           |                           |       |
|/applications/                             |GET    |Allow      |                           |                           |       |
