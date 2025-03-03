# Re-import transactions

The Firefly III data importer can recognise two different types of duplicate transactions. By default, it will refuse to import both of these types.

1. Duplicate entries in your files are skipped, unless you explicitly tell the data importer to import them anyway.
2. Firefly III itself will refuse to import transactions it believes already exist. You can overrule this.

Even when you **delete** the original transaction, importing it again will result in a duplication error. This is because many files come with dummy lines, and it's very annoying to have to keep deleting those.

If you want to reimport duplicate transactions after deleting them:

1. Turn off duplicate detection
2. Use the "purge"-button in your profile page to permanently remove deleted transactions

