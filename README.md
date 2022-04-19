# test-semantic-release
ddsdddsadsdsa
sarasa
dsddsdsdsdsd
more
dsds
asd
dsd
asdasdasda
porque
Running: npx semantic-release --ci true
asd asd
dsdsd
perf(pencil): remove graphiteWidth option 1.0.3 - 1.0.4 as
perf(pencil): remove graphiteWidth option
feat(pencil): add 'graphiteWidth' option   1.0.4  - 1.1.0
fix(pencil): add 'graphiteWidth' option  1.1.0  1.1.1 sd
dsdsd
asdasdas
dsdsddsdsddsadasd
ci(pencil): add 'graphiteWidth' nada
docs(pencil): add 'graphiteWidth' nada
sssdsd
ddddssss
sdsdsdd  ss
fix(pencil): stop graphite breaking when too much pressure applied
build: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
ci: Changes to our CI configuration files and scripts (examples: CircleCi, SauceLabs)
docs: Documentation only changes
feat: A new feature s 
fix: A bug fixd
perf: A code change that improves performance d
refactor: A code change that neither fixes a bug nor adds a feature
test: Adding missing tests or correcting existing tests

asdasd
breaking change

See release types for the release types hierarchy.

With the previous example:

Commits with type 'docs' and scope 'README' will be associated with a patch release.
Commits with type 'refactor' and scope starting with 'core-' (i.e. 'core-ui', 'core-rules', ...) will be associated with a minor release.
Other commits with type 'refactor' (without scope or with a scope not matching the glob core-*) will be associated with a patch release.
Commits with scope no-release will not be associated with a release type.
Default rules matching
If a commit doesn't match any rule in releaseRules it will be evaluated against the default release rules.

With the previous example:

Commits with a breaking change will be associated with a major release.
Commits with type 'feat' will be associated with a minor release.
Commits with type 'fix' will be associated with a patch release.
Commits with type 'perf' will be associated with a patch release.
Commits with scope no-release will not be associated with a release type even if they have a breaking change or the type 'feat', 'fix' or 'perf'.


//"preset": "angular",


https://github.com/semantic-release/commit-analyzer/blob/master/lib/default-release-types.js
https://github.com/semantic-release/commit-analyzer/blob/master/lib/default-release-rules.js


,
   "dryRun": true,
   "ci": true