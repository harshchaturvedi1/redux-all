###  FLUX architecture
- action -> dispatcher -> store -> view

or

- action -> dispatcher -> store -> view
-                |____<___action___<_|
                
```
Views react to changes in stores
Stores can only get updated through dipatchers
Dispatchers can only be triggerred by actions
Actions can only get triggered by Views
```