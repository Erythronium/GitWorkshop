# Welcome to the Wandelbots Git-Workshop

# Reference Log
## Explanation
You accidentally hard reset an important change and forced pushed it now you want to get the important commit back

## Steps
- Checkout reflog/feature
- Run ‚git reset --hard HEAD~1‘
- Run ‚git push --force‘
- Use reflog to find the state you want to get back to
- Hard reset to the state you want to get back to
- Push your changes
