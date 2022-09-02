# palindrome-javascript-by-ruido38.

function solution(str){
  let reversed = "";
  for (let i =  str.length -1; i >= 0; i--)
  {
    reversed += str[i]
  }
  
  return str === reversed
}
