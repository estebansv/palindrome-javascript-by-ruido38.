# palindrome-javascript-by-ruido38.
Given the string, check if it is a palindrome javascript by ruido38.
function solution(str){
  let reversed = "";
  for (let i =  str.length -1; i >= 0; i--)
  {
    reversed += str[i]
  }
  
  return str === reversed
}
