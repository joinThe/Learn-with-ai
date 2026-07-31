# Week 1 — React/React Native Performance Optimization

## Training covered
- Re-render mental model: state change, parent re-render, or context change
- `React.memo` — and the trap of unstable prop references (inline functions defeat it)
- `useCallback` / `useMemo` — when they help vs. unnecessary overhead
- `FlatList` optimization: stable `renderItem`, `keyExtractor`, `getItemLayout`, `windowSize`, `maxToRenderPerBatch`
- `FlashList` as a higher-performance alternative for large lists
- Context re-render pitfall — splitting contexts / memoizing provider values
- Profiling tools: React DevTools Profiler (web), Perf Monitor / Flipper (RN)

## Exercise assigned
Profile one screen in the existing project, identify one unnecessary re-render, fix it, and note the before/after.

## Findings
_(fill in after completing the exercise)_

- Screen profiled:
- Issue found:
- Fix applied:
- Before/after impact:
