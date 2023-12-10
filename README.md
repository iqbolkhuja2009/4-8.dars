4.8-dars
// function findElements(arr) {
//     if (arr.length < 5) {
//         console.log("Massiv uzunligi yetarli emas");
//         return;
//     }

//     let product = 1;

//     for (let i = 0; i < arr.length - 4; i++) {
       
//         let currentProduct = arr[i] * arr[i + 1] * arr[i + 2] * arr[i + 3] * arr[i + 4];
//         product *= currentProduct;
//     }

//     return product;
// }

// let myArray = [2, 3, 1, 4, 5, 2, 3, 1, 6, 7, 8, 9];
// let result = findElements(myArray);
// console.log("Natija:", result);

// 2-masala
// function createNewArray(wordsArray) {
//     let newArray = [];

//     for (let i = 0; i < wordsArray.length; i++) {
//         let word = wordsArray[i];
//         if (word.length > 0) {
//             newArray.push(word[0]);
//         }
//     }

//     return newArray;
// }

// let words = ["JavaScript", "Node", "React", "Angular"];
// let resultArray = createNewArray(words);
// console.log("Natija:", resultArray);

// 3-masala
// function createNewArrayFromOddNumbers(numbersArray) {
//     let newArray = [];

//     for (let i = 0; i < numbersArray.length; i++) {
//         let number = numbersArray[i];
//         if (number % 2 !== 0) {
//             newArray.push(number);
//         }
//     }

//     return newArray;
// }

// // Test qilish
// let numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
// let resultArray = createNewArrayFromOddNumbers(numbers);
// console.log("Natija:", resultArray);

// 4-masala
// function countOddNumbers(numbersArray) {
  
//     let oddCount = 0;

//     for (let i = 0; i < numbersArray.length; i++) {
//         let number = numbersArray[i];
//         if (number % 2 !== 0) {
//             oddCount++;
//         }
//     }

//     return oddCount;
// }

// let numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
// let result = countOddNumbers(numbers);
// console.log("Toqlar soni:", result);

// 5-masala
// function createNewArrayFromLongWords(wordsArray) {
//     let newArray = [];

//     for (let i = 0; i < wordsArray.length; i++) {
//         let word = wordsArray[i];
//         if (word.length > 5) {
//             newArray.push(word);
//         }
//     }

//     return newArray;
// }


// let words = ["JavaScript", "Node", "React", "Angular", "Programming"];
// let resultArray = createNewArrayFromLongWords(words);
// console.log("Natija:", resultArray);

// 6-masala
// function isTub(n) {
//     if (n < 2) {
//         return false;
//     }
//     for (let i = 2; i <= Math.sqrt(n); i++) {
//         if (n % i === 0) {
//             return false;
//         }
//     }
//     return true;
// }

// function tubSonlarSoni(massiv) {
//     let tubSonlarSoni = 0;

//     for (let i = 0; i < massiv.length; i++) {
//         if (isTub(massiv[i])) {
//             tubSonlarSoni++;
//         }
//     }

//     return tubSonlarSoni;
// }

// let massiv = [2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15];
// let natija = tubSonlarSoni(massiv);
// console.log(`Massivda ${natija} ta tub son bor.`);


// 7-masala
// function yigindi(massiv) {
//     let kopaytma = 1;

//     for (let i = 0; i < massiv.length; i++) {
//         if (massiv[i] % 7 === 0 && massiv[i] % 3 === 0) {
//             kopaytma *= massiv[i];
//         }
//     }

//     return kopaytma;
// }
// let massiv = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 12, 14, 21];
// let natija = yigindi(massiv);
// console.log(`Massivdagi 7 va 3 ga karrali elementlarining kopaytmasi: ${natija}`);
