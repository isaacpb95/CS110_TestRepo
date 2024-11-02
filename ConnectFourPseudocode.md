pseudocode for the connect four group project
use this as a refference to help write your code

```
initilizeBoard function {
  for each row in board {
    for column in row {
      set board[row][column] to ' '
    }
  }
return
}

displayBoard function {
  for each row in board {
    for each column in row {
      print every column seperated with '|'
    }
  print endl;
  }
return
}

dropPiece function {
  for row from bottom to top of board {
    if board[row][column] is ' ' {
      place piece
      return ture //place was successful
    }
  return false // place was unsuccessful
}

checkWinner function {
  // check horizontal win
  for each row in board {
    for each column in row {
      if 4 consecutive pieces {
        return true
      }
    }
  }

// check vertical win

// check diagonal top left to bottm right win

// check diagonal bottom left to top right win

return false
}


```
