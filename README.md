# www
Source coce for https://swiftists.com

## Building locally

### Installing Hugo

```sh
brew install hugo gh aspell
```

### Installing pyspelling

```sh
pip install pyspelling 
```

### Testing locally

```
hugo server
```

## Updating

1. Make changes
2. Test locally with `hugo server`
    i. Spellcheck with `pyspelling -c .spellcheck.yml`
3. Open a PR 
    ```sh
        gh pr create
    ````
4. Review and merge to `master`
5. GitHub actions will publish to https://wwww.swiftists.com automatically
