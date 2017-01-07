workspace(name = "com_github_monorepo_repo")

git_repository(
    name = "io_bazel_rules_go",
    tag = "0.3.2",
    remote = "https://github.com/bazelbuild/rules_go.git",
)
load("@io_bazel_rules_go//go:def.bzl", "go_repositories")

go_repositories()
