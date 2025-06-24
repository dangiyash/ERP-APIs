While going through the buzz I discovered that the ERP makers left the APIs to be accesible by anyone, so I used them. and detailed them for you so you can also use them directly and easily.



All requests go to: `https://erpapi.manit.ac.in/api/`

- **POST `/login`** — Authenticate with `{ username, password }` and get a JWT token. 
- **POST `/student_profile_check`** — Fetch your profile with `{ studentuid }`. 
- **POST `/fetch_semester`** — Get semester info with `{ studentuid, program }`. 
- **POST `/student_result`** — Your results, grades, and CGPA
- **POST `/check-fees-status`**  




