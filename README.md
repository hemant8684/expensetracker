# Expense Tracker (Spring Boot)

Simple Expense Tracker backend using Spring Boot, Hibernate (JPA) and PostgreSQL.

## Run

1. Ensure PostgreSQL is running and a database named `expense_db` exists.
2. Update credentials in `src/main/resources/application.properties` if needed.
3. Build and run:

```bash
mvn spring-boot:run
```

APIs:
- POST  /api/expenses
- GET   /api/expenses
- PUT   /api/expenses/{id}
- DELETE /api/expenses/{id}
- GET   /api/expenses/summary
