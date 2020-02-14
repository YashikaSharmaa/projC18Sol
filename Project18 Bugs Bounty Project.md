# Project- Bug Bounty Project C18

## Bugs-

### 1) Clouds is overlapping the Restart and gameOver sprite 

#### Solution

we have to change the depth of  clouds below that of  restart and gameOver 

CODE-

```javascript
 //CHANGE MADE-
    cloud.depth=restart.depth-1;
    cloud.depth=gameOver.depth-1;
    
```



