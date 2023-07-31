let outputF = document.getElementById('fahrenheit');
let area = document.querySelector('.area');
let circumference = document.querySelector('.circumference');
let diameter = document.querySelector('.diameter');
let pi = Math.PI;
let minutes = document.querySelector('.minutes');
let seconds = document.querySelector('.seconds');
let ounces = document.querySelector('.ounce')
let kg = document.querySelector('.kilogram')


//Temperature conversion function

function celsius(valnum) {
 outputF.innerHTML = (valnum * 9 / 5) + 32;
 console.log(outputF.innerText);
};

console.log(Math.PI)

//Circle formulae function 
let circle = radii => {
 area.innerHTML = Math.round(pi * (radii ^ 2)) + ' cm²';
 diameter.innerHTML = radii * 2 + ' cm';
 circumference.innerHTML = Math.round(pi * 2 * radii) + ' cm';
}


//Time unit functions

let timeConvert = hours => {
 minutes.innerHTML = hours * 60 + ' mins';
 seconds.innerHTML = hours * 3600 + ' seconds';
}

//Weight conversion

let weight = weight => {
 ounces.innerHTML = //Math.round
  (weight * 28.35) + ' ounces';
 kg.innerHTML = (weight / 1000) + 'kg';
}



//Sidenav toggle

function closeNav() {
 document.getElementById('sidenav').style.width = '0';
 document.getElementById('sidenav').style.transition = 'width 0.3s'
}

function openNav() {
 document.getElementById('sidenav').style.width = '100%';
 document.getElementById('sidenav').style.transition = 'all 0.3s'
}