# twitter-clone-warbler


                 USERS
        +----------------+
        | id             |
        | username       |
        | email          |
        | password       |
        +----------------+
          |          |
          |          |
          |          |
       messages    follows
          |
          |
    +-------------+
    |  MESSAGES   |
    +-------------+
    | id          |
    | text        |
    | timestamp   |
    | user_id FK  |
    +-------------+
          |
          |
        likes
          |
          |
    +-------------+
    |   LIKES     |
    +-------------+
    | user_id FK  |
    | message FK |
    +-------------+