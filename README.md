# icp-course

### 1.Lesson1-note

**DFX-new-project**

```
dfx new richard001 --no-frontend
```

**new HTML**

```
echo '<html><body><h1>Hello World!</h1></body></html>' > src/richard001_assets/assets/index.html
```

**Deploy contract/canister**

```
dfx deploy --network=ic --with-cycles=300000000000
```

**Query Balance** 

```
dfx wallet --network=ic balance
```

**Stop contract/canister**

```
dfx canister --network=ic stop --all
```

**Delete contract/canister**

```
dfx canister --network=ic delete  --all
```



