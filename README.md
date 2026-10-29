# Campus Bites

An information website for Campus Bites, a fictional university cafeteria. Students and staff can check the menu, the daily special and combo deals, how to place an order, and how to contact the cafeteria.

Built for DevOps Fundamentals (SEST4663), Assignment 01, Fall 2026. Plain HTML and CSS. No backend.

## Pages

| Page | File | Owner |
| --- | --- | --- |
| Home | `src/index.html` | Team Lead |
| Menu | `src/menu.html` | Member 1 |
| Daily specials and deals | `src/deals.html` | Member 2 |
| How to order | `src/order.html` | Member 3 |
| Feedback and contact | `src/feedback.html` | Member 4 |

All five pages use one stylesheet, `styles/style.css`. Each owner adds their styles in their own block of that file.

## Run it

Open `src/index.html` in a browser. There is nothing to install.

## Branches

- `main`: production-ready code. Changes arrive only through a pull request with 3 approvals.
- `develop`: all active development. Changes arrive only through a pull request with 2 approvals.
- `feature/<page-name>`: one branch per page, created from `develop`.
- `release/v1.0`: testing before the release goes to `main`.
