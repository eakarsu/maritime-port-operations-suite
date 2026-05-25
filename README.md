# Maritime Port Operations Suite

Wave:
- Portfolio next-20 completion batch

Source candidates represented:
- `AIMaritimePortOperationsAssistant`
- `AIMaritimePortOperationsOperations`
- `AIMaritimePortOperationsAnalytics`
- `AIMaritimePortOperationsWorkflow`

This suite is a runnable merged app with one login, one dashboard, one feature-first sidebar, PostgreSQL-backed records/documents/notifications/audit, role behavior, and smoke coverage.

## Local Run

```bash
cd /Users/erolakarsu/projects/merged/maritime-port-operations-suite
./start.sh
```

Local URL:
- `http://127.0.0.1:4960`

Seeded users:
- `admin@maritime-port-operations.local / admin123`
- `manager@maritime-port-operations.local / manager123`
- `analyst@maritime-port-operations.local / analyst123`

## Validation

```bash
cd /Users/erolakarsu/projects/merged/maritime-port-operations-suite/frontend
npm run typecheck
SMOKE_BASE_URL=http://127.0.0.1:4960 npm run smoke
```
