# Eduhubb2
I'll start by exploring the EduHub workspace to see what's already in place, then build the home page to match your wireframe.

Setting up Tailwind and the core project structure, then building the home page to match your wireframe.

Prompt for EduHub Frontend
You are an expert Senior Angular 16 Architect, UI/UX Engineer, and Software Architect.
Your responsibility is to build ONLY the frontend for the EduHub application.
The backend is developed by another teammate. Never modify backend APIs. Treat the Backend API Collection as the single source of truth.

==========================

TECH STACK

==========================

- Angular 16 (Class Based)

- Tailwind CSS 3.4.17

- TypeScript

- Angular Router

- HttpClient

- RxJS

- Angular Animations

- JWT Authentication



==========================

STRICT RULES

==========================

1. Every component must contain:

   - component.html

   - component.ts

   - component.css

2. Business logic belongs only in TypeScript.

3. Tailwind utility classes belong only in HTML.

4. No Bootstrap.

5. No Angular Material unless requested.

6. No inline styles.

7. Use Reactive Forms.

8. Services perform all API communication.

9. Components never call HttpClient directly.

10. Use Observables throughout.





==========================

PROJECT STRUCTURE

==========================

src/app

  components/

  models/

  services/

  guards/

  interceptors/

  shared/

  assets/



Create models:

- User

- Login

- Course

- Enrollment

- Material

- Feedback



Create services:

- AuthService

- CourseService

- EnrollmentService

- MaterialService

- FeedbackService



Create guards:

- AuthGuard

- RoleGuard



Create interceptor:

- JwtInterceptor



## FEATURES



### Home

- Hero carousel, featured courses, categories, testimonials, CTA, FAQ, footer.



### Login

- JWT login, remember me, validation, password toggle.



### Registration

- Role selector, validation, confirm password.



### Educator Dashboard

- Statistics, manage courses, materials, enrollments, feedback.



### Student Dashboard

- Browse courses, enroll, view materials, feedback.



### Courses

- Search, filter, sort, pagination, loading, empty state.



### Materials

- Cards with icons, download/open links.



### Feedback

- CRUD feedback with toast notifications.



### Navigation

- Sticky navbar, responsive sidebar.



### Error Pages

- 404, 401, 500.

==========================

DESIGN SYSTEM

==========================

Theme:

- Black

- White

- Gray
Border radius: rounded-2xl

Cards: glassmorphism

Shadow: soft-xl

Spacing: generous

Icons: Heroicons/Lucide

Animations:

- fade

- slide

- scale

- stagger

- route transitions

Buttons:

- hover scale

- ripple feel

Forms:

- floating labels

- inline validation

Tables:

- sticky header

- pagination

- sorting

- search
==========================

ROUTING

==========================

Public:

/

login

register



Educator:

dashboard

courses

add-course

edit-course/:id

materials

feedback

enrollments



Student:

dashboard

courses

my-courses

materials

feedback



Unknown route -> 404

Unauthorized -> 401 page

==========================

AUTHENTICATION

==========================

Store:

token

role

userId



Attach Authorization:

Bearer <token>



Redirect users by role after login.



## IMPLEMENTATION CHECKLIST



1. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



2. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



3. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



4. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



5. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



6. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



7. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



8. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



9. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



10. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



11. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



12. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



13. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



14. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



15. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



16. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



17. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



18. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



19. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



20. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



21. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



22. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



23. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



24. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



25. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



26. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



27. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



28. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



29. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



30. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



31. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



32. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



33. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



34. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



35. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



36. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



37. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



38. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



39. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



40. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



41. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



42. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



43. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



44. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



45. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



46. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



47. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



48. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



49. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



50. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



51. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



52. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



53. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



54. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



55. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



56. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



57. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



58. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



59. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



60. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



61. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



62. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



63. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



64. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



65. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



66. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



67. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



68. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



69. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



70. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



71. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



72. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



73. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



74. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



75. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



76. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



77. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



78. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



79. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



80. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



81. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



82. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



83. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



84. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



85. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



86. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



87. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



88. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



89. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



90. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



91. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



92. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



93. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



94. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



95. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



96. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



97. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



98. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



99. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.



100. Build feature incrementally. Preserve existing code. Write reusable components. Add loading, error, success states. Ensure responsive layout. Use Tailwind utilities. Comment important methods. Validate forms. Use services for API integration.

# EduHub Backend API Collection



## Base URL

`http://localhost:8080`



### Headers

```

Authorization: Bearer <JWT_TOKEN>

Content-Type: application/json

```



---



# Authentication



## POST /api/register

Access: Public

Request:

```json

{

  "username":"John Doe",

  "email":"john@example.com",

  "mobileNumber":"9876543210",

  "password":"Pass@123",

  "userRole":"Educator"

}

```

Response:

```json

{"message":"User created successfully!"}

```



## POST /api/login

Access: Public

Request:

```json

{

  "email":"john@example.com",

  "password":"Pass@123"

}

```

Response:

```json

{

  "token":"JWT_TOKEN",

  "role":"Educator",

  "userId":1

}

```



---



# Course APIs



## GET /api/course

Role: Student, Educator



## GET /api/course/{courseId}

Role: Student, Educator



## POST /api/course

Role: Educator

```json

{

  "courseId":0,

  "title":"",

  "description":"",

  "courseStartDate":"2026-01-01",

  "courseEndDate":"2026-04-01",

  "category":"",

  "level":""

}

```



## PUT /api/course/{courseId}

Role: Educator

(Same body as Add Course)



## DELETE /api/course/{courseId}

Role: Educator



---



# Enrollment APIs



## GET /api/enrollment

Role: Student, Educator



## GET /api/enrollment/{enrollmentId}

Role: Student



## GET /api/enrollment/user/{userId}

Role: Educator



## GET /api/enrollment/course/{courseId}

Role: Educator



## POST /api/enrollment

Role: Student

```json

{

  "enrollmentId":0,

  "userId":1,

  "courseId":2,

  "enrollmentDate":"2026-01-01",

  "status":"Pending"

}

```



## PUT /api/enrollment/{enrollmentId}

Role: Student

(Same body as Add Enrollment)



## DELETE /api/enrollment/{enrollmentId}

Role: Student



---



# Material APIs



## GET /api/material

Role: Student



## GET /api/material/{materialId}

Role: Student, Educator



## GET /api/material/course/{courseId}

Role: Student, Educator



## POST /api/material

Role: Educator

```json

{

  "materialId":0,

  "courseId":1,

  "title":"",

  "description":"",

  "url":"",

  "uploadDate":"2026-01-01",

  "contentType":"PDF"

}

```



## DELETE /api/material/{materialId}

Role: Educator



---



# Feedback APIs



## GET /api/feedback

Role: Educator



## GET /api/feedback/{userId}

Role: Student



## POST /api/feedback

Role: Student

```json

{

  "userId":1,

  "feedbackText":"Excellent Course",

  "date":"2026-01-01"

}

```



## DELETE /api/feedback/{feedbackId}

Role: Student



---



# Common Status Codes



- 200 OK

- 201 Created

- 400 Bad Request

- 401 Unauthorized

- 403 Forbidden

- 404 Not Found

- 500 Internal Server Error



---



# Entity Models



## User

```json

{

  "userId":0,

  "username":"",

  "email":"",

  "mobileNumber":"",

  "password":"",

  "userRole":"Educator"

}

```



## Course

```json

{

  "courseId":0,

  "title":"",

  "description":"",

  "courseStartDate":"",

  "courseEndDate":"",

  "category":"",

  "level":""

}

```



## Enrollment

```json

{

  "enrollmentId":0,

  "userId":0,

  "courseId":0,

  "enrollmentDate":"",

  "status":"Pending"

}

```



## Material

```json

{

  "materialId":0,

  "courseId":0,

  "title":"",

  "description":"",

  "url":"",

  "uploadDate":"",

  "contentType":"PDF"

}

```



## Feedback

```json

{

  "feedbackId":0,

  "userId":0,

  "feedbackText":"",

  "date":""

}

# EduHub Frontend Folder Architecture



src └── app ├── components │ ├── home │ ├── login │ ├── registration │

├── navbar │ ├── usernav │ ├── adminnav │ ├── educatoraddcourse │ ├──

educatorviewcourse │ ├── educatoreditcourse │ ├── educatoraddmaterial │

├── enrollmentlist │ ├── studentviewcourse │ ├── mycourse │ ├──

useraddfeedback │ ├── userviewfeedback │ ├── adminviewfeedback │ └──

error ├── models │ ├── user.model.ts │ ├── login.model.ts │ ├──

course.model.ts │ ├── enrollment.model.ts │ ├── material.model.ts │ └──

feedback.model.ts ├── services │ ├── auth.service.ts │ ├──

course.service.ts │ ├── enrollment.service.ts │ ├── material.service.ts

│ └── feedback.service.ts ├── guards │ ├── auth.guard.ts │ └──

role.guard.ts ├── interceptors │ └── jwt.interceptor.ts ├── shared │ ├──

loader │ ├── confirm-dialog │ ├── toast │ ├── table │ └── cards └──

assets ├── images ├── icons └── animations



Coding Rules - Observable-based services - No API call inside

component - Reactive forms only - Route guards - Global error handling -

Responsive design - Reusable components

