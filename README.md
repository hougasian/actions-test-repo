# actions-test-repo

- one (worked)
- two (~~failed after setting development to default branch~~)
- three (worked on merge) 
- four 
  - changed to `if: github.event.pull_request.merged == true`
  - job no longer shows as running on initial pr
  - didn't merge to master
- replaced alll branch types
  - types: [opened, synchronize, reopened, closed]
  - skipping correctly on development
  - did not run on merge
- removed merged === true
  - types: [closed] 
  - set back to [opened, synchronize, reopened, closed]
  - set master back to default - still failed
  - new push, action check no present on initial PR
- may have updated   