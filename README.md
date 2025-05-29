Spring Boot Day 2 Exercise
Exercise Title: Build REST APIs for User Entity
Objective:
You are continuing to develop the backend for the employee management system. Today you will:
- Create a User entity
- Set up JPA Repository
- Build RESTful APIs using Spring Boot
- Connect with MySQL and verify CRUD operations
Requirements:
1. Create a User class with fields: id (Long), name (String), email (String).
2. Annotate it with @Entity and map fields properly.
3. Create UserRepository interface extending JpaRepository.
4. Create a UserService class with methods to get all users and create a new user.
5. Create a UserController class with endpoints:
 - GET /api/users - to fetch all users
 - POST /api/users - to add a new user
6. Use @RestController and @RequestMapping annotations.
7. Test using Postman to create and retrieve users.
Bonus Task (Optional):
Add validation to the User model using annotations like @NotNull or @Email, and handle validation
exceptions using @ControllerAdvice.
Submission Checklist:
- REST APIs working and tested
- User data saved in MySQL
- Proper structure: model, repository, service, controller
- Code compiles and runs without error
Time Allocation:
Task | Time
--------------------------|------
User Entity Creation | 45 mins
Repository Setup | 30 mins
Service and Logic | 1 hr
Controller + APIs | 1.5 hr
Testing via Postman | 1 hr
Debugging and Q&A | 1 hr
Wrap-up + Recap | 15 mins
