use reclaim policy

should to change default storage class, because standard(default) kubernetes  storage class reclaim policy is delete but we want to retain it.
therefore we create another storage class with retain reclaim policy and set it to default

## use diffrent storge(hard for nodes) for high performance
