### Redux
- global state management for react applications

###  FLUX architecture
- action -> dispatcher -> store -> view

or

```
- action -> dispatcher -> store -> view
-                |____<___action___<_|
```
                
```
Views react to changes in stores
Stores can only get updated through dipatchers
Dispatchers can only be triggerred by actions
Actions can only get triggered by Views
```


### Three core principals of redux
- Single Source of Truth:
- State is READ only
- Changes in Redux are made with pure functions


### Actions
{
    type:"type-of-action",
    payload:{}
}

### Dispatcher
dispatch(action)
- this will trigger some change in the state

### Reducer
- specify how application's state changes in response to action sent to the store

```
e.g.
switch(type){
    case():{}
    
}
```