# Coding-Challenge-2
U2863-9518

// 1. calculate the tip
let bill = 275;
let tip = (bill >= 50 && bill <= 300) ? bill * 0.15 : bill * 0.20;
// 2. output details
console.log(`The bill was ${bill}, the tip was ${tip}, and the total value ${bill + tip}`);
// 3. create a function
function calcTip(bill) {
    return (bill >= 50 && bill <= 300) ? bill * 0.15 : bill * 0.20;
}
