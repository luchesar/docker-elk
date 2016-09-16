After installing you need to register a gitlabrunner using the folowing command:

```gitlab-ci-multi-runner register --non-interactive --name local-sbt --tag-list "docker,shell" --url https://gitlab.bgoner.com/ci --registration-token sYNq6M-Q-hY1etGNNgbP --executor shell```

Please get the registration token from the Gitlab web interface.
