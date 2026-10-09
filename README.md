# Totalum mobile builds

The `codemagic.yaml` Totalum uses when a Totalum user builds their mobile app on their own Codemagic account
("bring your own Codemagic API key" in the project's Mobile apps section). Totalum adds this repository as an app in
that Codemagic account and starts its workflows with per-build variables; the code that is built is the project's
own saved source, downloaded at the start of each build.

Kept identical to the workflows of Totalum's starter project (only the source step differs: a build always needs a
saved version).
