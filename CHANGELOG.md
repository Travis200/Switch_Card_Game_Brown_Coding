# CHANGELOG

* v1.1.0 [2019-11-08]: Added a SmartAI computer opponent.
  Added strategy players.SmartAI
  None of the bugs have been fixed.

* v1.1.0 [2019-10-25]: First major release.
  This version is known to contain some bugs.
  
  Moved ```game = Switch()``` and ```game.run_game()``` to outside of the class.
  
  Corrected error in line 157 of switch.py: ```for i in: range(1, n):``` &rarr; ```for i in: range(1, n+1):```
  
  Corrected error in line 6 of cards.py ```values = '2 3 4 5 6 7 8 9 10 J Q K A'.split()```   
  &rarr;  ```values = '2 3 4 5 6 7 8 9 10 J Q K A'.split()```
  
  Corrected error in line 178 of switch.py ```if card.value in 'QA':``` &rarr; ```if card.value in 'Q' or 'A':```
  
  Corrected errors in lines 104, 109, 114 in switch.py (in respective order):  
  ```self.skip == False``` &rarr; ```self.skip = False```  
  ```self.draw2 == False``` &rarr; ```self.draw2 = False```  
  ```self.draw4 == False``` &rarr; ```self.draw4 = False```
  
  Corrected error in line 226 of switch.py ```elif card.value == '4':``` &rarr; ```elif card.value == 4:```
  
  Corrected error in line 257 of switch.py```sizes = sizes[:idx] + sizes[idx:]``` &rarr; 
  ```sizes = sizes[idx:] + sizes[:idx]```
  
  
  
  
 
 
  

  
  
  
  
  
  
