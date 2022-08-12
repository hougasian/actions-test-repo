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