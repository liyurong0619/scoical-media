Main Contribution: Homepage Design — Social Feed Wall | Spring Boot × Vanilla JS
A community platform inspired by Instagram, featuring post publishing, user interactions, and a notification system.
Backend

RESTful API handling post creation, editing, deletion, and paginated loading, with Spring Security for authentication and unauthorized access protection
Image upload pipeline includes format validation and compression (resized to 1080px max), supporting a two-step flow of crop-then-upload

Frontend

Implemented in pure Vanilla JS: infinite scroll, image carousel with indicators, and drag-to-crop preview; responsive design supports multiple screen sizes
Image upload supports two modes: crop mode (mouse and touch drag) and direct upload
Client-side notification system: likes and comments instantly generate notifications; clicking a notification auto-scrolls to the corresponding post
