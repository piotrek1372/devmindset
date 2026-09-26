# Example review

Check the actual changed file and platform. For Python: compile, run with a small safe input, validate positive CLI ranges, close resources, and document platform requirements. For Bash: `bash -n`, ShellCheck if available, safe quoting, predictable failure behavior and expected empty pipelines. For gawk: run a representative sample fixture, check expected output and state GNU-specific dependencies.

For every example, verify the article URL, requirements, safe invocation, expected observation, limitations and README index. Review error paths and avoid unsupported “production-ready” claims. For benchmarks, share workload and seed between methods, document cache/order effects and report environment. A tool missing locally means a check is pending, not passed.
