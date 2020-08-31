# 1351.-Count-Negative-Numbers-in-a-Sorted-Matrix

```C#
  public class Solution {
    public int CountNegatives(int[][] grid) {
   
        int bound0 = grid.GetUpperBound(0);
        
        int count =0;
        
        for(int i=0; i<=bound0; i++){
            for(int j=0; j<grid[i].Length; j++){
                
                if(grid[i][j] < 0){
                    ++count;                   
                }
            }
        }
        
        return count;
    }
}
```

## Complexity Analysis
 
