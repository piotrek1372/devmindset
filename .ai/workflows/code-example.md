# Example workflow

1. Read the relevant live article and current example repository tree. Keep the existing directory-to-article mapping consistent.
2. Describe what behavior the code should demonstrate and where the platform or kernel may vary.
3. Implement a focused, independently runnable example. Document dependencies, invocation, expected output and limitations; link the article.
4. Run the checks in `quality/examples.md` and capture environment and observations. Use safe fixtures; do not attach `strace` to an unrelated production process for a smoke test.
5. Review article/code agreement and update the examples README index when adding a directory. Report any unverifiable claim instead of asserting success.

Changes to the examples repository are separate work; this memory file is not executable verification.
