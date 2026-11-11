# chat_room_project

A real-time chat app with rooms. Users enter a display name, join a room by
name, and exchange live, timestamped messages with everyone in that room. The
app will be publicly accessible through GitHub Codespaces.

**Implementation plan:** [docs/IMPLEMENTATION_PLAN.md](docs/IMPLEMENTATION_PLAN.md)
covers every step, what it achieves, what to test, and the commit to push.

## Planned stack

React + Vite + Tailwind · Node.js + Express + Socket.IO · SQLite · Vitest +
Playwright · GitHub Actions · GitHub Codespaces

## Hosting limitations

Codespaces public ports make the app reachable by anyone with the URL, but only
while the codespace is running. It has an idle timeout of 5–240 minutes and a
maximum lifetime of 12 hours per run. Use a persistent host for 24/7
availability.

Display names are guest identities, not secure logins, and rooms are public to
anyone who knows the room name.
