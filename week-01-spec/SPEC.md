# TaskFlow — Specification

## 1. Problem
<!-- 3–5 lines: who the user is and what problem the app solves. -->

## 2. User stories
<!-- At least 8. Format: As a user, I want … so that … -->
1. As a user, I want to create a task with a title and due date so that I don't forget it.
2. TODO
3. TODO
4. TODO
5. TODO
6. TODO
7. TODO
8. TODO

## 3. MVP vs later
| Story # | MVP (8 weeks) | Later |
|---|---|---|
| 1 | ✅ | |
| TODO | | |

## 4. Data model

### User
| Field | Type | Notes |
|---|---|---|
| id | integer | primary key |
| username | string | unique |
| TODO | | |

### Task
| Field | Type | Notes |
|---|---|---|
| id | integer | primary key |
| title | string (max 200) | required |
| description | text | optional |
| priority | choice: low / medium / high | |
| status | choice: todo / doing / done | default todo |
| due_date | date | |
| created_at | datetime | set automatically |
| owner | FK → User | one user has many tasks |

## 5. Screens
<!-- Link your 4 wireframes: login, task list, task form, task detail. -->
- Login: `docs/wireframes/login.png`
- Task list: TODO
- Task form: TODO
- Task detail: TODO

## 6. API draft
| Method | URL | What it does |
|---|---|---|
| GET | /api/tasks/ | List my tasks |
| TODO | | |

## 7. Stack
| Layer | Technology | Role |
|---|---|---|
| Front end | HTML, CSS, JavaScript → React | TODO |
| Back end | TODO | TODO |
| Database | TODO | TODO |
| Hosting | TODO | TODO |
