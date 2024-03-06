# Book-Record

server creation >> storing book data
                >> User register
                >> Subscriber

##  /user

    >> POST: (Create account)
    >>Get: (Get all details)


## /user/{id}
    >> GET: (User info by id)
    >> PUT: (update user by id)
    >>DELETE: (Delete user by id (Before deleting check for outstanding books && fines))


## /user/subscription-details/{id}
    >>GET: User subscription details
        >> Date of subscription
        >> DUe fines
        >> Valid till


## /books
    >>GET: Get all the books
    >>Post: Add new books