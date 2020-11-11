# demo-app

```
$ copilot app init    # create a new copilot application
$ copilot env init    # create a new environment but use an existing VPC
$ copilot svc init    # create your new service
$ copilot deploy    #  deploy the new service
```

```
copilot pipeline init \
--github-url https://github.com/mdxp/demo-app.git \
--github-access-token file://myGitHubToken \
--environments "dev"
```
