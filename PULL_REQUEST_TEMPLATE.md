## What this changes

<!-- One or two sentences. Link the issue: Closes #123 -->

## How it was tested

- [ ] Unit tests
- [ ] Integration tests (Postgres, non-superuser role) if data access changed
- [ ] Checked in the browser if UI changed (light and dark)

## Checklist

- [ ] No real candidate data in code, fixtures or screenshots
- [ ] New tenant-scoped tables are added to `TENANT_TABLES`
- [ ] Migrations are included and chained after the current head
