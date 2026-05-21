# student-task-planner
🎓 StudyFlow — Student Task & Study Planner
StudyFlow is a fully functional, single-page student productivity application built using pure HTML, CSS, and JavaScript — no frameworks, no libraries. It was developed as a frontend evaluation project to demonstrate core web development concepts.

🛠️ Concepts Demonstrated
1. DOM Manipulation
All content on the page — tasks, schedule blocks, timer, stats, and quotes — is dynamically created and updated using JavaScript DOM methods like createElement, innerHTML, textContent, and querySelector. Nothing is hardcoded in HTML.
2. Events
User interactions are handled through event listeners and onclick handlers — including button clicks for adding/deleting/completing tasks, tab switching, timer controls, filter chips, and the quote refresh button.
3. LocalStorage
All user data is saved directly in the browser using localStorage.setItem and localStorage.getItem. This means tasks, study sessions, and schedule blocks persist even after the page is closed or refreshed. No backend or database is needed.
4. Fetch API
A motivational quote is fetched from a live external API (quotes-api-self.vercel.app) every time the page loads, using the fetch() function with async/await. If the API is unavailable, a fallback set of quotes is shown — demonstrating proper error handling with try/catch.
