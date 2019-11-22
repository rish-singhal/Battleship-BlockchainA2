## Implementation Details
- How solidity contract is interacting with js...?
  --> "basic"
- 1,2,3,4,5 -> {Naag,Dhanush ,Trishul,MahaKaal, Brahmos}
- map( index ==> length )
Game Components -->
- Point Struct{
    left,up,down, right
    }
- torp. struct{
    type,P,Q,bool(attack)
    }
- torp. array
- initBoard(player1){
      js...
  10x10,  
      }
      
- saveBoard(array){ --- > sol
      torp. ini}
      
- initBoard --> sol.
- 4 - 10x10 arrays , 2-initial , 2-bool (attack)
- updateAttack(player1, int x, int y){
    BOOL(plyr1)[x,y] == 1:
      return 'no move'
    [x,y] = 1;
    }
- showBoard(player1){
    ....... bool2, init1}
- showOppBoard(player1){
    ....... init2, bool1}
- chckgamestate(){
    return --> points
    when points == max. :
      'game over', 'winner'
    }  
 
- Game ID
