# Muslim Nova site

The public pages the stores ask for: privacy policy, terms of use and the
account deletion request page, in Arabic and English. Served by GitHub
Pages from `main`; plain HTML and one stylesheet, no scripts, no trackers.

The privacy policy describes exactly what the app sends
(`docs/store-readiness.md` in the app repository); change both together.

`SUPPORT_EMAIL_PENDING` marks where the support email goes. The check
workflow fails while it is present, and the app's release build refuses it
too: replace it everywhere before publishing.
