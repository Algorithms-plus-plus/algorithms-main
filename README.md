# algorithms-main
Building FE and BE

# Repo
To work with the repo in synchronous manner the following commands should be followed:
1. Update the submodules in the main repository:
```
git submodule update --remote
git add <submodule-path>
git commit -m "Update submodule to latest version"
```

2. Push the changes to the main repository:
```
git push
```

3. In the other repositories, pull the changes from the main repository:
```
git pull
git submodule update
```

[More info](https://labex.io/tutorials/git-how-to-synchronize-changes-in-a-git-submodule-417934).

Frameworks and modules:
1. Spring Boot 3.5.3
- WebFlux - idea is not the reactive approach but to get partial data from single request instead of using sockets. Need to check if it works, if not will use sockets
- Modulith - a way to separate different modules and exclude the possibility referencing internal dependencies. Don't think events will be used between the modules. (Domain Driven Design)
2. Angular 20
- bootstrap 5+
