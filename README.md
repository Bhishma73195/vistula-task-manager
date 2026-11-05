# Task Manager – Team Project (IT)

Student ID: **73195**  
Repository: https://github.com/vistula-team-project-73195/vistula-task-manager  
Application (after GitHub Pages is enabled): https://vistula-team-project-73195.github.io/vistula-task-manager/

## Technology
HTML, CSS, JavaScript, GitHub Pages, Supabase PostgreSQL REST API.

## Requirements implemented
- Display tasks
- Create, edit, complete/incomplete and delete tasks
- Persist tasks via the Supabase REST API
- Show status/error messages
- Contributor page reads the ID from `contribution.json`

## Database setup
1. Create a **dedicated demonstration-only** Supabase project.
2. In the SQL Editor, run [setup/supabase.sql](setup/supabase.sql).
3. Update `config.json` with the project URL and the **publishable** API key
   (never use a secret or service_role key). Leave `tableName` as `tasks`.
4. Test create, read, edit, complete and delete from the deployed website.

**Warning:** This assignment requires completely public CRUD access. Anyone on
the internet can change tasks. Never put sensitive information in the demo table.

## GitHub Pages
Open Settings → Pages → Deploy from a branch → main → /(root).
Verify the deployment at:
https://vistula-team-project-73195.github.io/vistula-task-manager/

## Team collaboration
The existing contributor files show student **72564**. However, to satisfy
the assignment, they **must be introduced through a merged PR authored by
the partner**, not simply committed directly by the repository owner.
The owner must also create a separate PR into their partner's repository,
and that PR must be merged.

- **Incoming partner PR**: add the actual merged PR URL
- **Outgoing PR**: add the actual merged PR URL

## Submission
Submit **only** the working GitHub Pages application URL to Platon once
Supabase functionality and both Pull Requests are verified.
