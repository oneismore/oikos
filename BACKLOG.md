# Backlog

Feature requests and planned extensions. Entries here will **not** be implemented until explicitly prioritized and moved into a release branch.

New suggestion? → [Open an issue](https://github.com/ulsklyc/oikos/issues/new?template=feature_request.md) or add it here.

## Open Entries

| ID | Issue | Feature | Notes |
|----|-------|---------|-------|
| BL-11 | [#10](https://github.com/ulsklyc/oikos/issues/10) | Contacts: CardDAV (read-only) provider | Sync address book entries from phone/server; backend lib evaluation needed |

---

## Completed Features (Reference)

| ID | Feature | Version |
|----|---------|---------|
| BL-01 | Calendar: Expand recurring events (RRULE) | v0.3.0 |
| BL-02 | Budget: Monthly comparison (current vs. previous month) | v0.3.0 |
| BL-03 | Meal plan: Drag & drop between slots and days | v0.3.0 |
| BL-04 | Calendar sync: Wire up settings UI completely | v0.3.0 |
| BL-05 | Budget: Auto-generate recurring entries | v0.3.0 |
| BL-06 | Shopping: Quick-add autocomplete | v0.3.0 |
| BL-07 | Notes: Full-text search / filter | v0.4.0 |
| BL-08 | Dashboard: Weather widget refresh | v0.4.0 |
| BL-09 | Contacts: vCard import / export | v0.4.0 |
| BL-10 | PWA: Offline fallback for critical pages | v0.4.0 |
| - | UX Polish (animations, bottom sheet, FAB, stagger, vibration) | v0.2.0 |
| - | Event listener leaks, CSS gaps, modal tests | v0.2.1 |
| - | Internationalisation system (de + en), locale picker, formatDate/Time | v0.5.0 |
| - | PWA: Correct Oikos icons (192/512/maskable/apple-touch), service worker v22 | v0.5.1 |
| - | Calendar: Fix all-day RFC 5545 DTEND, DURATION support, birthday sync | v0.5.6 |
| - | Calendar: RRULE expansion fix (strip RRULE: prefix), YEARLY support | v0.5.7 |
| - | Italian (it) localization (497 keys) | v0.5.8 |
| - | Swedish (sv) localization (548 keys) - contributed by @olsson82 | v0.11.3 |
| - | Security hardening: XSS, rate limiter bypass, OAuth CSRF, CSV injection, session invalidation | v0.5.9 |
| - | Budget: Fix update failing when category changes | v0.6.0 |
| - | Upgrade bcrypt 5 → 6, ESM migration, structured logger, remove SESSION_SECRET fallback | v0.7.0 |
| - | XSS fix: shared esc() utility, deduplicate escHtml across all modules | v0.7.1 |
| - | Dashboard: Shopping list widget (lists with open items, progress bar, item preview) | v0.8.0 |
| - | Tasks: optional "None" priority level (default for new tasks, hides badge) | v0.9.0 |
| - | Tasks: persist kanban/list view in localStorage; ?view=kanban URL parameter | v0.9.1 |
| - | Meals: customizable meal type visibility (breakfast/lunch/dinner/snack toggles in Settings) | v0.10.0 |
| - | Budget: configurable currency (13 currencies selectable in Settings → Budget) | v0.11.2 |
| - | Swedish (sv) translation contributed by @olsson82 | v0.11.3 |
| - | Shopping: custom categories - add, rename, delete, reorder in Settings | v0.12.0 |
| - | Meals: optional recipe link per meal (recipe_url field, link icon on card) | v0.13.0 |
| - | Spanish (es) translation - all sections fully translated | v0.14.0 |
| - | Settings: categorized tab navigation (General, Meals, Budget, Shopping, Calendar, Account) | v0.16.0 |
| - | Budget: CNY (Chinese Yuan) added to currency list (#42) | v0.16.2 |
| - | i18n: French (fr), Turkish (tr), Russian (ru), Greek (el), Chinese Simplified (zh) locales | v0.16.3 |
| - | Budget: TRY (Turkish Lira) and RUB (Russian Ruble) added to currency list | v0.16.3 |
| - | i18n: Japanese (ja), Arabic (ar), Hindi (hi), Portuguese (pt) locales (567 keys each) | v0.19.0 |
| - | Budget: AED (UAE Dirham), BRL (Brazilian Real), INR (Indian Rupee), SAR (Saudi Riyal) added to currency list | v0.19.0 |
