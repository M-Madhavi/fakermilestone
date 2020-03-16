# fakermilestone
creating changes to faker
const faker = require('faker');

let bikename = faker.name.bikename();
let bikecc = faker.name.bikecc();

let bikecompany = faker.name.bikecompany();
let model = faker.name.model(); 
let colour = faker.name.colour();
let cost = faker.name.cost();
let  showroomlocation= faker.name.showroomlocation();

let phone = faker.phone.phoneNumber();

console.log(`bike: ${model} ${bikename} ${bikecc} ${colour}`);
console.log(`company: ${bikecompany}`);
console.log(`showroomlocation: ${showroomlocation}`);
console.log(`Phone: ${phone}`);
