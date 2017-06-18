Clone repo

Modify `program.jq`

Build zip with `./build`

Create openwhisk action:

```
wsk action create myJqAction exec.zip --docker
```

ref: http://jamesthom.as/blog/2017/01/16/openwhisk-docker-actions/
