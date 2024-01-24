```
src/App.vue:5:9 - error TS2322: Type 'Ref<Map<string, UnwrapRefSimple<K>>>' is not assignable to type 'Ref<Map<string, K>>'.
  Type 'Map<string, UnwrapRefSimple<K>>' is not assignable to type 'Map<string, K>'.
    Type 'UnwrapRefSimple<K>' is not assignable to type 'K'.
      'K' could be instantiated with an arbitrary type which could be unrelated to 'UnwrapRefSimple<K>'.

5   const m: Ref<Map<string, K>> = ref(new Map<string, K>())
          ~

```