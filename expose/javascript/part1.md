1. `values added: 20`

2. `final result: 20`

3. We should not use `var` as it is function-scoped and not blocked-scoped, which allows it to be accessed outside of the block.

4. `values added: 20`

5. This will return an error as `let` is blocked-scoped and thus can only be accessed within the block rather than the whole function.

6. This will throw an error as `const` cannot be changed so line 7 will cause an error.

7. This will also throw an error as the issue is the same with `const` not being reassingnable.