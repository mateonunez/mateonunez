<div align="center">
   <img src="https://github.githubassets.com/images/mona-loading-default.gif" alt="mateonunez github" width="69" align="center" />
</div>

<br />

```javascript
const { repositories } = @mateonunez

useEffect(() => { 
   repositories.forEach(repo => !repo.forked && fork(repo)) 
}, [repositories])
```
