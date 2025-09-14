# Opticlass – School Registration & Onboarding Flow

This flow shows how schools, admins, teachers, students, and parents are registered and onboarded in the Opticlass MVP.

---

## **Registration & Onboarding Steps**

1. **School Registration**
   - School admin fills out the registration form with:
     - School Name
     - Type (Boarding / Day / Private / Public)
     - Location
     - Admin Contact Name & Email
     - Phone Number
     - Password
   - Optional email verification for the admin.

2. **Admin Dashboard Creation**
   - After registration, a school dashboard is automatically created.
   - The admin can manage teachers, students, and parents.

3. **Adding Teachers**
   - Admin adds teacher accounts manually or via CSV import.
   - Teachers receive login credentials.
   - Teachers are assigned classes and subjects.

4. **Adding Students**
   - Admin or teachers add student accounts manually or via CSV import.
   - Students are assigned to classes and sections.

5. **Adding Parents**
   - Admin or teachers add parent accounts manually.
   - Parents are linked to their child’s profile.
   - Parents receive login credentials to track student performance.

6. **System Ready**
   - Students, teachers, and parents can now access the system.
   - Classes, assignments, grades, and attendance tracking begin.

---

## **Mermaid Diagram – School Onboarding Flow**

```mermaid
flowchart TD
    A[School Registration Form] --> B[Admin Verification / Email Confirmation]
    B --> C[School Dashboard Created]
    C --> D[Add Teachers]
    C --> E[Add Students]
    C --> F[Add Parents]
    D --> G[Teachers Login & Assigned Classes]
    E --> H[Students Login & Assigned Classes]
    F --> I[Parents Login & Linked to Children]
    G --> J[System Ready for Classes & Assignments]
    H --> J
    I --> J
