# GitHub action Pronamic deploy

Deploy your WordPress plugin file to the Pronamic plugin directory with this GitHub action.

## Errors

```
GraphQL: Resource not accessible by integration (repository.latestRelease)
```

For private repositories, read access to the contents is required to request the latest release.

```
    permissions:
      contents: 'read'
```

https://docs.github.com/en/rest/releases/releases?apiVersion=2022-11-28#get-the-latest-release

## Links

- https://cli.github.com/manual/gh_repo_view
- https://docs.github.com/en/rest/releases/releases?apiVersion=2022-11-28#get-the-latest-release
- https://github.blog/changelog/2021-04-20-github-actions-control-permissions-for-github_token/
