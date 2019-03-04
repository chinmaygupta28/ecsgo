# ecsgo
Cli to manage AWS ECS clusters

### Goals
Cli should be 
1. Describe ecs things.
2. Able to create ecs ops work simply.
3. Extensible.
4. Add non ecs custom resource related task.

### Plans

1. Clusters
  - [ ] list
  - [ ] group with prefix/suffix (prod/stag/xxx)

2. Services
  - [ ] list (default - all services), filter with cluster-name.
  - [ ] group with prefix/suffix (prod/stag/xxx)

3. Tasks
  - [ ]  list default -all, filter with cluster-name (default-all), service-name

4. Task definition
  - [ ] list all structured fields required task-name:revision(default-revision:latest), filter with --field field1, --field field2.
