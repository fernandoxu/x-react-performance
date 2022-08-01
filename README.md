# React Performance

## code split

- lazy + suspense
- eager loading (lazy + suspense + onFocus/onMouseEnter)
- webpack magic comment (webpackPrefetch)

## useMemo for Expensive Calculations

- wrap a function in useMemo to memoize expensive results
- use web worker in some cases

## React.memo for Reducing re-renders

## Optimize Context Value

- memoize context value
- separate the contexts

## Fix Perf Death by a Thousand Cuts

- colocate state
- separate context
- consuming components
- slice of App state
- use recoil

## Production Performance Monitoring
