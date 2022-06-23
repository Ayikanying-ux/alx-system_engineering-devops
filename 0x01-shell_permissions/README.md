*su Betty*

```Change the current user to user Betty```

*id -un*

```prints the effective username of the current user```

*groups*

```prints all the groups the current user is part of```

*chown betty hello*

```changes the owner of the file hello to the user betty```

*touch hello*

```creates an empty file called hello```

*chmod u+x hello*

```adds execute permission to the owner of the file hello```

*chmod u+x,g+x,o+r hello*

```adds execute permission to the owner and the group owner, and read permission to other users, to the file hello```

*chmod u+x,g+x,o+x hello*

```adds execution permission to the owner, the group owner and the other users, to the file hello```
