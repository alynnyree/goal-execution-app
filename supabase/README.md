# What is in here

`app-api.ts` is the whole of the `app-api` Supabase function in one file,
ready to paste into the Supabase website.

It is BUILT from the real source files, which live in the other repository
(`alynnyree/strat-journal-app`, under `goal-app/`) together with the checks
that run against it. Nobody edits this copy by hand. It is replaced whenever
the real files change, so a pasted copy cannot drift from the copy under test.

To tell a fresh paste from a stale one, search the code for: `x-app-key`
