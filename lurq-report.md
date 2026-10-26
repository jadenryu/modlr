```
lurq, upgrade check on .

UNVERIFIED  1 package(s), not checked, NOT declared safe:
    · next: next/font/google: no readable surface (entry resolved but no exports found)

TYPES     checked 6 package(s) in the files that import them
TYPES     not checked for 6 package(s):
    · @ai-sdk/xai: the new version's types import zod/v4, which is not installed here
    · react, three: the new version ships no type definitions of its own
    · next: the new version's types import node:stream, react-dom/static, which is not installed here
    · @jgphilpott/polyslice: no tsconfig.json includes the files that import it
    · @paper-design/shaders-react: the new version's types import react, which is not installed here

OK        15 package(s), no referenced symbols removed

note: autopilot is set to 'pr' for this repository in lurq, but this workflow is pinned to 'fix' mode, so it will open pull requests with only the changes lurq can prove, and will not run the agent. Re-copy .github/workflows/lurq-upgrade.yml from your dashboard to let the setting govern runs.
```
