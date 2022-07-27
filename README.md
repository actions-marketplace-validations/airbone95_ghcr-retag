# ghcr-retag
retag images in ghcr without pulling them

## variables
this action uses the following inputs (all are required):
| Variable      | Description                                                                    | Example             |
|---------------|--------------------------------------------------------------------------------|---------------------|
| old_tag       | the old tag that you want to assign a new tag to (old tag will NOT be deleted) | latest              |
| new_tag       | the new tag you want to assign to the tag above                                | production          |
| ghcr_username | credentials to access ghcr                                                     | myuser              |
| ghcr_password | credentials to access ghcr                                                     | supersecretpassword |
| ghcr_repo     | the docker image you want to assign the new tag to                             | myuser/mycontainer  |
