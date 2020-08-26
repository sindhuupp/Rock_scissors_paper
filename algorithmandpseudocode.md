 Algorithm
1.create a computerplay function.
2.this function  selects randomly 'Rock' 'scissors' and 'paper'
3.create a new function 
4.that function should take two inputs and declares winner
5.requirements:
    a.function should be case sensitive
    b.and value should be returned to function
6.challenge:
    call a new function game and play the game for 5 rounds and declare the winner
                        Pseudo code                    
computerplay()
return randomly [Rock Scissors paper]

                        1 round play
finalwinner()
let x = players input;
convert players input to lower case
let y = computers input;
if ((x= rock && y= paper)||
   (x= paper && y= scissors)||
   (x= scissors && y=rock)||)
{ print "you loose"}
else if( (x= rock && y= rock)||
         (x= paper && y= paper)||
         (x= scissors && y= scissors))
    {print " you tie"}
else if( (x=rock && y= scissors)||
         (x=paper && y= rock)||
         (x=scissors && y=paper))
        {print "you won"
         }
else{
    print please enter a valid input
}


                          if playing 5 times

finalwinner(){
for (loop 5 times)
{
let x = players input;
convert players input to lower case
let y = computers input;
    let playermarks=0;
    let computermarks=0;
  if ((x= rock && y= paper)||
   (x= paper && y= scissors)||
   (x= scissors && y=rock)||)
   {print "you loose"
 computermarks++ }
else if( (x= rock && y= rock)||
         (x= paper && y= paper)||
         (x= scissors && y= scissors))
    {print " you tie"}
else if( (x=rock && y= scissors)||
         (x=paper && y= rock)||
         (x=scissors && y=paper))
        {print "you won"
         playermarks++}
else{
    print please enter a valid input
}
if(playermarks>computermarks)

{print "you are the final winner for 5 games"}

elseif(playermarks==computermarks)

{print "you tie with the computer"}

else
{print "sorry you loose to the computer"}
}
call the finalwinner function to know the final result