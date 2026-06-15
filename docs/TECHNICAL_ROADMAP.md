# Technical Roadmap

## Problem

The current app is a strong prototype, but it is built as a single-course app. The next phase is to generalize the code so new curated courses can be added without duplicating the whole app.

## Phase 1: Platform Foundation

1. Create a generic course model with course id, title, slug, category, description, level, modules, lessons, flashcards, formulas, quizzes, practice problems, and mock exams.

2. Move course content out of app logic. Course data should live in a course-content area instead of being mixed into rendering and navigation code.

3. Add a course catalog. The home screen should show available courses. The existing course should appear as one course card, not as the entire app identity.

4. Add course-scoped progress. Progress, quiz answers, flashcard mastery, checklist items, and preferences should be stored by course id instead of hardcoded single-course keys.

5. Create reusable learning engines: course catalog, course dashboard, lesson viewer, quiz engine, flashcard deck, formula bank, practice problem viewer, mock exam mode, and progress dashboard.

## Phase 2: Product Experience

- Course landing pages
- Continue studying button
- Weak-topic recommendations
- Study streaks
- Exam readiness score per course
- Search within a course
- Arabic/simple-summary support per lesson

## Phase 3: Commercial Readiness

- Authentication
- Paid course access
- Admin course publishing workflow
- Course analytics
- Versioned course updates
- Mobile-friendly UI polish

## Immediate Rule

Do not add more hardcoded single-course behavior. Every new feature should be designed as reusable platform infrastructure.