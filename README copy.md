# ELOYCE University — Smart Campus Assistance System (Supabase + Role-Based Auth)

## Default Login Credentials
- **Student Account 1:** `alex@eloyce.edu` | Password: `student123` (Accesses Student Portal, Submit Request & Track Requests only)
- **Student Account 2:** `samira@gmail.com` | Password: `123456` (Accesses Student views only)
- **Admin Account:** `admin@eloyce.edu` | Password: `admin123` (Accesses Authority Admin Dashboard & Ticket Status Controls only)

## Connecting Your Supabase Project
1. Open your Supabase project and run the SQL inside `supabase_schema.sql` in the **SQL Editor**.
2. Copy your **Project URL** and **Anon Public Key** from **Project Settings -> API**.
3. Either paste them directly in the app modal under **Supabase DB Config**, or set `DEFAULT_SUPABASE_URL` and `DEFAULT_SUPABASE_ANON_KEY` in `js/app.js`.
