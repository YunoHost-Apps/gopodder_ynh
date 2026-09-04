goPodder does one thing: it keeps your podcast subscriptions and episode progress in sync across devices and apps. **Just synchronization, done well.**
- Works with AntennaPod, gPodder, Cardo, and anything else that speaks the gPodder sync protocol
- Built-in web UI for managing accounts, users, devices, and subscriptions
- REST API with API key auth for scripts, provisioning, and custom integrations
- Multi-user support with admin/standard roles, per-account user limits, optional self-registration
- SQLite by default (zero config), PostgreSQL if you need it
- Share your subscriptions publicly via OPML and RSS links
- No outbound connections. The server never phones home, never fetches feed URLs, never resolves external DNS. Your subscription data stays on your box
- Single binary, no dependencies, ~13 MB RAM at idle. Runs fine on a Raspberry Pi
