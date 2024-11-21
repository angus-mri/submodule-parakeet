# submodule-parakeet

## Commands run
### Setup
`git submodule add <turbo-url> shared-submodule`

`git submodule update --init --recursive`

### Updating the submodule from here
`cd shared-submodule/shared-submodule`

`nano code.cs`

Change the file

`git add *`

`git commit -m "Update submodule"`

`cd ../..`

`git add *`

`git commit -m "Update submodule pointer`


These changes updated the submodule repo as well as the submodule here


### Updating the submodule from Turbo-parakeet
Make changes and commits in turbo-parakeet

Come back here

`cd shared-submodule`

`git fetch`

`git checkout main`

`git pull origin main`

`cd ..`

`git add shared-submodule`

`git commit -m "Update submodule to latest turbo-parakeet commit`

`git push`

