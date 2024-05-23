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
// 4. utilize arrays
    //data set 1 bills: 275, 40, 430
let bills1 = [275, 40, 430];
let tips1 = bills1.map(calcTip);
let totals1 = bills1.map((bill, i) => bill + tips1[i]);
console.log(bills1);
console.log(tips1);
console.log(totals1);
    //data set 2 bills: 125, 555, 44
let bills2 = [125, 555, 44];
let tips2 = bills2.map(calcTip);
let totals2 = bills2.map((bill, i) => bill + tips2[i]);
console.log(bills2);
console.log(tips2);
console.log(totals2);
