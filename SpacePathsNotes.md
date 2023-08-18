

## Questions on SPACE paths

|                                     | Stored as block? | Stored as name + size block? | Stored as path? | Stored as tree path? | Visualized as path? | Visualized as tree path? | returned as path by functions? | returned as tree path by functions? |
| ----------------------------------- | ---------------- | ---------------------------- | --------------- | -------------------- | ------------------- | ------------------------ | ------------------------------ | ----------------------------------- |
| /map facet                          |                  |                              |                 |                      |                     |                          |                                |                                     |
| /parent facet                       |                  |                              |                 |                      |                     |                          |                                |                                     |
| Pointer Events                      |                  |                              |                 |                      |                     |                          |                                |                                     |
| Nested object (connected in facets) |                  |                              |                 |                      |                     |                          |                                |                                     |

### Block for pointers events: 

1) `[name(bound) size(pair) name(bound) size(pair)]`
2) `[name(unbound) size(pair) name(unbound) size(pair)]`
3) `[object! size(pair) object! size(pair)]`

### Block for other events pointers: 

1) `[name(bound) name(bound) name(bound)]`
2) `[name(unbound) name(unbound)]`
3) `[object! object! object!]`

### Red Paths

1) `name(bound)/name(bound)/name(bound)`

2) `name(unbound)/name(unbound)/name(unbound)`

### Tree paths

Stored only as block? 

1) yes

2) no

   if no: stored as?

   1) URL

   2) Other (no block)________________________________________________________


      
      URL or other storage has words bound to space objects?

      1) yes
      2) no

