# User Registeration
# From user persepective
1. form fillup
2. Click registeration button

# From developer percepctive
1. Destructuring form data (eg:- Fullname, email, password)
2. Vlidation of form data (eg:- All fields are required)
3. Check email from database (eg:- must be unique)
4. Hash the password
5. Send token and store it to frontend (either in localhost or in cookies)
6. Store it to database
7. Send message(https status code , main-for now)
- 200 ("Success Response"),
- 201 ("New data create")
- 400("Bad request")
- 401("Not found")
- 500("Internal server error")
