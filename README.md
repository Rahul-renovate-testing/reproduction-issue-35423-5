Test regex filtering:

`baseBranchPatterns: ["!//test"]`

Should create update PRs on branch which do not have `test` string in them ie. `main`, `random1`, `random2`
