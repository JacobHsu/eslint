## useEffect 

[How to fix missing dependency warning when using useEffect React Hook?](https://stackoverflow.com/questions/55840294/how-to-fix-missing-dependency-warning-when-using-useeffect-react-hook)

To disable the rule you would write it like

```js
useEffect(() => {
   // other code
   ...

   // eslint-disable-next-line react-hooks/exhaustive-deps
}, []) 
```
