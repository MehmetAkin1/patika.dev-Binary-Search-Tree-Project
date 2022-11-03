# patika.dev-Binary-Search-Tree-Project  
Proje 3
# [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.    

# Binary Search Tree Aşamaları  

1. Dizinin başındaki değer 7 olduğu için; root = 7  
Dizinin içinde 7'den sonraki eleman eğer 7'den büyük ise root'un sağ tarafına, küçük ise sol tarafına yazılır.     

2. Böylelikle 2. Aşamamız = 5<7 | 5, 7'nin soluna yazılır.  

             7    
           /    
         5      
          
3. 1 değeri, sırasıyla 1<7 ve 1<5 olduğu için; 1, kendinden bir önce gelen kendinden büyük elemanın soluna yazılır   

                      7  
                    /    
                  5  
                /    
              1   
                
 
4. 8 değeri için 8>7 olduğundan 8, 7'nin sağına yazılır.  
  
                   7
                 /   \ 
               5      8
              /  
             1   
               
5. 3 değeri sırasıyla 3<7, 3<5, 3>1 olduğu için 1'in sağına yazılır.  
 
                    7
                  /   \ 
                5       8   
              /  
            1  
              \  
                3  
                               
6. 6 değeri 6<7 fakat 6>5 olduğu için 5'in sağına yazılır.  
  
                       7  
                     /   \
                    5      8
                   /  \ 
                  1    6
                    \  
                      3   
                      
 7. 0 değeri sırasıyla 0<7, 0<5, ve 0<1 olduğu için 7>5> 1'in soluna yazılır.  
 
                          7  
                        /   \  
                       5     8  
                     /   \  
                    1     6  
                  /   \  
                 0     3  
                 
8. 9 değeri, sırasıyla 9>7 ve 9>8 olduğu için 8'in sağına yazılır.  

                         7  
                       /   \  
                      5     8  
                    /   \     \  
                   1     6      9  
                 /   \  
                0      3   
                
9. 4 değeri sırasıyla 4<7, 4<5, 4>1 ve 4>3 olduğu için 3'ün sağına yazılır.  

                        7  
                      /   \  
                    5       8  
                  /   \       \  
                 1     6       9  
               /   \  
              0      3  
                       \  
                         4  
                         
10. 2 değeri sırasıyla 2<7, 2<5, 2>1, 2<3 olduğu için 3'ün soluna yazılır.  

                          7  
                        /   \  
                      5       8  
                    /   \       \  
                  1       6       9  
                /   \  
              0       3   
                    /   \  
                  2       4    
                  
                  
# www.patika.dev                  
                  
                  
                  

                     

                        
                   
  
  
  
  
  
  
  
  
  
  
  
  
  


