
function countLetters(spacedString) {

var string = spacedString.split(' ').join('');
var letters = {};

  for (var i = 0; i < string.length; i++) {
    var currentLetter = string[i];
// console.log(currentLetter);
    if (letters[currentLetter] === undefined) {
      letters[currentLetter] = i + " ";
// console.log(letterPosition);
    } else {
      letters[currentLetter] += i + " ";
    }
  }
  return letters;

}

console.log(countLetters("lighthouse in the house"));
