npm install
// to install the dependencies
npm run serve
// to run the build


ALGORITHM

Factorial:

function factorialize(num) {
  if (num === 0 || num === 1)
    return 1;
  for (var i = num - 1; i >= 1; i--) {
    num *= i;
  }
  return num;
}
factorialize(5);

IQ TEST:

question 1: answer is 2
question 2: answer is 2
question 3: answer is 3
question 4: answer is 4
question 5: answer is 3 