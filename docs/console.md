# Console commands

## GIT

create a new repo with Github CLI

```ps2  

mkdir OutlookServer

cd OutlookServer

git config --global init.defaultBranch trunk

git init

gh repo create


# alternative accepting defaults
# gh repo create OutlookServer --public --confirm

```

## Dotnet CLI

- Install Dotnet EF

    ```ps2
    dotnet tool install --global dotnet-ef
    ```

- Create a webAPI project
  
  ```ps2
  dotnet new webapi --name OutlookServer --output OutlookServer --framework net6.0
  ```
