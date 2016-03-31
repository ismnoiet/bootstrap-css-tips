#Bootstrap CSS Tips
Well,it is not tips but essential functionalites that developers need often 
and are not mentioned in the official documentation.

###Bootstrap v3
**Listen for modal close event:**
```javascript
$('modal-select').on('hidden.bs.modal', function (){
                 	// do something here.  
                  });
```

