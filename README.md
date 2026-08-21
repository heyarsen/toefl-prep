# TOEFL Prep

A focused, free TOEFL Complete the Words practice MVP.

## MVP

- No account required
- 120 original practice questions
- 10-question sessions
- Fixed missing-letter blanks
- Live timer and progress
- Instant results and answer review
- Responsive mobile/desktop UI
- Google AdSense integration
- Lightweight event analytics via `dataLayer`
- SEO metadata and canonical URL

## Structure

```text
TOEFL
└── Tasks
    └── Complete the Words
        ├── questions.js
        ├── Practice Session
        └── Results
```

The app is intentionally static and inexpensive to host. Additional task types can later be added as separate question datasets and task modules without requiring authentication or a backend for the basic practice experience.

## Analytics events

The MVP pushes these event names to `window.dataLayer`:

- `landing_page_view`
- `practice_started`
- `question_answered`
- `practice_completed`
- `practice_restarted`
- `result_viewed`

Connect the data layer to the chosen analytics provider when deploying.
